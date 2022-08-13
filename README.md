# IHP Backend Twitter Clone Example App

[You can find this app running here.](https://ihp-backend-twitter-clone.vercel.app/)

## Usage

On first -d start install the npm dependencies:

```bash
npm install
```

Set the `BACKEND_URL` in `.env` to your project's url:

```bash
# .env
BACKEND_URL=https://REPLACE ME.di1337.com
```

After this you can start the web server and esbuild watcher:

```bash
npm run dev
```

## Entrypoint

The entrypoint of this app is `app.tsx`.

## Schema

If you want to import this frontend into your own IHP Backend, copy the contents of Schema.sql into your project.
