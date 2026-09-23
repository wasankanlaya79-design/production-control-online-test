# Production Control Online Test

V1.35 online integration test using Vercel + Supabase.

Routes:
- `/` home
- `/operator` operator mobile
- `/executive` executive PC dashboard
- `/executive-mobile` executive mobile dashboard

All live counters read/write `public.production_events` in the same Supabase project.
