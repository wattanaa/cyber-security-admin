# Cyber Security (Admin)

This is source code for leaning about frontend
## Clone
```bash
git clone https://github.com/prawee/cyber-security-admin.git
cd cyber-security-admin
npm install
```

## Security
```bash
cp env.simple .env
```

## Database
```bash
npx prisma db push
npx prisma studio
```

## Development

Run the dev server:

```shellscript
npm run dev
```

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying Node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `npm run build`

- `build/server`
- `build/client`

## Styling

This template comes with [Tailwind CSS](https://tailwindcss.com/) already configured for a simple default starting experience. You can use whatever css framework you prefer. See the [Vite docs on css](https://vitejs.dev/guide/features.html#css) for more information.
