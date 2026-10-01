# StudentHub SA — Supabase starter

## Configure
Open `supabase-config.js` and replace `PASTE_YOUR_SB_PUBLISHABLE_KEY_HERE` with the publishable key from Supabase → Settings → API Keys. Keep the quotes. The Project URL is already set.

Use only the `sb_publishable_...` key. Never place an `sb_secret_...` or `service_role` key in browser files.

## Run
Keep all files in the same folder. Open `index.html` in a modern browser with internet access, or upload the folder to a static website host.

## Add listings
In Supabase → Table Editor → `listings`, insert rows. Required: `category`, `title`, `description`. Category must be one of `resource`, `bursary`, `job`, `accommodation`. Set `status` to `published`. Optional: `subject`, `grade`, `location`, `price`, `deadline`, `url`.

## Notes
- Email confirmation may be required before a new user can log in.
- Students can read published listings and save/remove their own listings.
- This package intentionally has no public admin panel. Do not create a policy allowing every visitor to insert or edit listings.
- Before launch, test signup, confirmation, login, saving, logout, and listing visibility.
