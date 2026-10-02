# Aura POS

Restaurant & café point-of-sale app built with React, TanStack Start, Vite and Supabase.

## Vercel deployment

This deployment package is configured for Vercel and does **not** require AI/Lovable AI environment variables.

The public Supabase URL and publishable key are included in the client configuration, so the app can start without adding public Supabase variables in Vercel.

### Deploy

1. Upload this project to GitHub.
2. Import the repository into Vercel.
3. Keep the framework as TanStack Start / use the included `vercel.json`.
4. Deploy.

### Optional admin environment variable

`SUPABASE_SERVICE_ROLE_KEY` is only required for server-side actions that manage other user accounts, such as creating/resetting/deleting staff or using the developer admin area. Do **not** expose this key to client-side code.

## AI

The menu AI/recommendation feature has been removed from this deployment package. The POS, recipes, inventory, QR ordering, KDS, reports, settings and normal authentication remain.
