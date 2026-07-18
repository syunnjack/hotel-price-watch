# Hotel Price Watch

宿泊空室・価格下落アラート

## Repository

Recommended repository name: `hotel-price-watch`

## Domain candidates

First candidate: `hotelpricewatch.jp`

Other candidates:

- `hotelpricewatch.jp`
- `stayprice.jp`
- `akiyasu.jp`
- `hotelalert.jp`

## Concept

指定エリア、日程、条件の空室と値下げを通知し、予約アフィリエイトと有料ウォッチへ誘導する宿泊アラート。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- ホテル予約成果報酬
- 有料ウォッチ
- 広告枠
- 旅行保険送客
- メールスポンサー

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
