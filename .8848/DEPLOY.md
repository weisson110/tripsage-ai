
## 8848 Fork Notes

This is a personal fork deployed at **https://8848.team**.

### Changes from upstream
- `NEXT_PUBLIC_APP_NAME` defaults to `8848 Travel AI`
- OpenRouter is the primary AI provider (works with the user's existing OpenRouter account)
- `vercel.json` kept unchanged (60s function timeout)
- Supabase migration scripts customized for personal single-user use

### Deployment
- Vercel project: `8848-team-ui` (existing) → will be aliased to point at this repo
- Production URL: https://8848.team
- Supabase project: user-managed (see SUPABASE_SETUP.md)
