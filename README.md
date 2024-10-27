# A SolidStart experiment

Based on the SOFA methodology I want to try out these things in no particular order:

- Add an ORM to the project, I would like to try [DrizzleORM](https://orm.drizzle.team/)
- Maybe setup a dev-container for development and ease of use with a database like Postgres
- Get familiar with SolidJS to see if I like it

## Functionality

The project will do:

- authentication
- display of the users
- display of some messages sent by the users

> Below is the default solid start readme me content

Everything you need to build a Solid project, powered by [`solid-start`](https://start.solidjs.com);

## Creating a project

```bash
# create a new project in the current directory
npm init solid@latest

# create a new project in my-app
npm init solid@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

Solid apps are built with _presets_, which optimise your project for deployment to different environments.

By default, `npm run build` will generate a Node app that you can run with `npm start`. To use a different preset, add it to the `devDependencies` in `package.json` and specify in your `app.config.js`.

## This project was created with the [Solid CLI](https://solid-cli.netlify.app)
