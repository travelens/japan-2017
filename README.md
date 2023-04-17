# Tasmania 2018

We visited Japan in 21 March to 1 April 2017. The trip was organised by Dan Campbell of [InsideJapan Tours](https://www.insidejapantours.com/).

Dan created a fantastic itinerary for us. We started with a few days of Tokyo, then headed down south to Okayama and Hiroshima, before returning via Osaka and Kyoto.

All in all, it was a fantastic journey, and I hope the following blog pages captures some of the magic from that trip.

## 🚀 Project Structure

Inside this project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   └── image.jpg
│   ├── components/
│   │   └── Card.astro
│   ├── content/
│   │   └── article.md
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

In addition, each trip will be stored as a separate repository in the
`travelens` organization. This project integrates all the individual
repositories into a single seamless website.

## 🧞 Commands

`yarn` is used as a package manager
All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `yarn`          | Installs dependencies                            |
| `yarn dev`          | Starts local dev server at `localhost:3000`      |
| `yarn build`        | Build your production site to `./dist/`          |
| `yarn preview`      | Preview your build locally, before deploying     |
| `yarn astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `yarn astro --help` | Get help using the Astro CLI                     |
