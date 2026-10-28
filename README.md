# Wang Tat 工作紀錄 (PWA)

Internal work-log web app for **Wang Tat Engineering Equipment Co. Limited**.

Site: **https://nwwang.github.io/wangtat-worklog-web/**

## Features

- Keyword search
- Separate 有保養 / 無保養 storage
- Monthly files (e.g. `11月 November, 2026`) with JSON/CSV export
- **雲端同步** via Supabase free tier (anon key baked into build; protected by RLS)

## Phone tip

If you already had logs only on one phone, open the updated site **on that phone first** once — it will auto-upload local logs to the cloud (one-time). Then other devices will see them.

## GitHub Pages

Source: branch `main` / folder `/docs`.
