This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

#### Install dependencies
First let's install the dependencies:

```bash
yarn
```

#### Set up authentication
You'll need an access token from Algora. Navigate to your [user settings](/user/settings/applications) to create one

![](https://app.algora.io/algora/w23/raw/branch/master/docs/create-access-token.png)

Then, create a file named `.env` at the project root with your access token:

```
ACCESS_TOKEN=e5fbf5cb060f753e865dfbfd84da5aad8341fa8d
```

#### Start the server & codegen

Now you are ready to run the development server:

```bash
yarn dev
```

Once the server starts, you also need to run the code generator on the side which generates types as you write your queries & mutations.

```bash
yarn codegen --watch
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

The GraphQL Playground can be accessed on [http://localhost:3000/api/graphql](http://localhost:3000/api/graphql).

## Learn More

To learn more about technologies used in this project, take a look at the following resources:


- [GraphQL](https://graphql.org/learn/) - introduction to GraphQL
- [graphql-codegen](https://www.the-guild.dev/graphql/codegen/docs/getting-started) - introduction to GraphQL Code Generator
- [Tailwind CSS](https://tailwindcss.com/) - the CSS framework of our choice
- [Headless UI](https://headlessui.com/) - UI components that integrate well with Tailwind CSS
- [Heroicons](https://heroicons.com/) - SVG icons
- [Next.js](https://nextjs.org/docs) - Next.js features and API
