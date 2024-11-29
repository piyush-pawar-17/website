# Website

This is the second iteration of my website with new design and blog included.

### Tech Stack

-   [Next.js](https://nextjs.org/)
-   [TypeScript](https://www.typescriptlang.org/)
-   [Tailwind CSS](https://tailwindcss.com/)
-   [MDX](https://github.com/mdx-js/mdx)

### Overview

-   `pages/api/*` - [API Routes](https://nextjs.org/docs/api-routes/introduction) for the post views.
-   `data/blogs/*` - Static blogs powered by [MDX](https://github.com/mdx-js/mdx).
-   `/pages/*` - Other Static Pages

### Running Locally

-   Clone the repo

```sh
git clone https://github.com/piyush-pawar-17/website.git
cd website
```

-   Install dependencies

```sh
yarn
```

-   Run dev server

```sh
yarn dev
```

Create a `.env.local` file at the root similar to `.env.example`
