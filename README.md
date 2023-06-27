# Soo you want to create a blog with nextjs 13?

[![Build and Deploy a Blog with Next.js 13 | React, Tailwind.css, Sanity.io | Tutorial 2023](https://img.youtube.com/vi/MqmzrQ1MNG8/0.jpg)](https://www.youtube.com/watch?v=MqmzrQ1MNG8)


-------------



- [Next.js](https://nextjs.org/)
- [Tailwind.css](https://tailwindcss.com/)
- [Sanity.io](https://www.sanity.io/)


  ### Commands you will need
```sh
npm install -D @tailwindcss/typography

```

```sh
npm install @portabletext/react @sanity/image-url next-sanity next-themes

```


## Deployment

After having run the `create-remix` command and selected "Vercel" as a deployment target, you only need to [import your Git repository](https://vercel.com/new) into Vercel, and it will be deployed.

If you'd like to avoid using a Git repository, you can also deploy the directory by running [Vercel CLI](https://vercel.com/cli):

```sh
npm i -g vercel
vercel
```

It is generally recommended to use a Git repository, because future commits will then automatically be deployed by Vercel, through its [Git Integration](https://vercel.com/docs/concepts/git).

## Development

To run your Remix app locally, make sure your project's local dependencies are installed:

```sh
npm install
```

Afterwards, start the Remix development server like so:

```sh
npm run dev
```

Open up [http://localhost:3000](http://localhost:3000) and you should be ready to go!

If you're used to using the `vercel dev` command provided by [Vercel CLI](https://vercel.com/cli) instead, you can also use that, but it's not needed.
