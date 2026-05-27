# Hong Ha Competitor Analysis Dashboard

Unified web app for competitor product scanning and data export.

## Features

- Professional dashboard for Thiên Long and Shopee product data.
- Thiên Long public catalog/product scanner through a serverless proxy.
- Shopee public API scanner with CSV/XLSX export.
- Combined Data Center view for cross-source analysis.
- Vercel-ready static frontend and serverless API routes.

## Deploy

This repository is structured for Vercel:

```text
public/      Static dashboard
api/         Vercel serverless functions
lib/         Shared API helpers
vercel.json  Routing and function config
```

Shopee interactive browser login is only available in the local desktop version. The Vercel version uses public API requests only.
