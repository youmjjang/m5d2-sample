# m5d2-sample

Minimal Render Web Service startup scaffold. This is **not** an implementation of any assignment-specific features.

## Local run

Requires Node.js 20 or newer.

```bash
npm start
```

- `GET /` — simple readiness message
- `GET /health` — JSON health response

## Render settings

- Runtime / Language: **Node**
- Root Directory: repository root (blank)
- Build Command: `npm install`
- Start Command: `npm start`
- Health Check Path: `/health` (optional)

The server binds to `0.0.0.0` and uses `process.env.PORT`.
If Render is not connected to this repository, connect `youmjjang/m5d2-sample` on the `main` branch first.
