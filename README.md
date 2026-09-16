# SquadVault — Next.js + Supabase starter

## Run locally
1. Install Node.js 20+.
2. Copy `.env.local.example` to `.env.local`.
3. Put your Supabase project URL and publishable key into `.env.local`.
4. Put the authorized admin WhatsApp number in `NEXT_PUBLIC_ADMIN_WHATSAPP` using country code, without `+`.
5. Run:
   npm install
   npm run dev
6. Open http://localhost:3000

## Connect Supabase
1. Open Supabase Dashboard → SQL Editor.
2. Paste and run `supabase/schema.sql`.
3. In Authentication → Providers, enable Email.
4. In Storage, create a bucket named `listing-images` if you add image-upload UI.
5. Add secure storage policies before allowing public uploads.

## Deploy
Push this project to GitHub and import it into Vercel. Add the same environment variables in Vercel.

## Important
This starter does not implement eFootball account transfer/sale functionality. It is designed for permitted gaming products/services and admin-supervised support. Do not collect passwords, recovery codes, or other credentials.
