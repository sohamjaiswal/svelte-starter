<!-- 
# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment. -->
# How to run (dev)

Make sure ports 5555 and 5173 are free.

Install Docker on your machine with compose and cd into the project dir and run `docker-compose up` or `docker compose up` depending on your docker + compose installation.

Now open your web browser and go to url http://localhost:5555 (prisma studio). Here open the Roles model and add the roles USER and ADMIN. 

Now you can open http://localhost:5173 (svelte app) and make your user account and assign it ADMIN role from prisma studio.

Congrats! Setup is complete, happy developing!