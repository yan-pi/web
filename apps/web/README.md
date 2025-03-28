0d1321
1d2d44
3e5c76
748cab
f0ebd8

# Portfolio Blog Starter

This is a porfolio site template complete with a blog. Includes:

- MDX and Markdown support
- Optimized for SEO (sitemap, robots, JSON-LD schema)
- RSS Feed
- Dynamic OG images
- Syntax highlighting
- Tailwind v4
- Vercel Speed Insights / Web Analytics
- Geist font

## Demo

https://portfolio-blog-starter.vercel.app

## How to Use

You can choose from one of the following two methods to use this repository:

### One-Click Deploy

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=vercel-examples):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/examples/tree/main/solutions/blog&project-name=blog&repository-name=blog)

### Clone and Deploy

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [pnpm](https://pnpm.io/installation) to bootstrap the example:

```bash
pnpm create next-app --example https://github.com/vercel/examples/tree/main/solutions/blog blog
```

Then, run Next.js in development mode:

```bash
pnpm dev
```

Deploy it to the cloud with [Vercel](https://vercel.com/templates) ([Documentation](https://nextjs.org/docs/app/building-your-application/deploying)).

{
"name": "web",
"version": "0.1.0",
"type": "module",
"private": true,
"scripts": {
"dev": "next dev --turbopack --port 3000",
"build": "next build",
"start": "next start",
"lint": "next lint --max-warnings 0",
"check-types": "tsc --noEmit"
},
"dependencies": {
"@tailwindcss/postcss": "4.0.0-alpha.13",
"@vercel/analytics": "^1.1.3",
"@vercel/speed-insights": "^1.0.9",
"geist": "1.2.2",
"next": "15.3.0-canary.14",
"next-mdx-remote": "^4.4.1",
"postcss": "^8.4.35",
"react": "18.2.0",
"react-dom": "18.2.0",
"sugar-high": "^0.6.0",
"tailwindcss": "4.0.0-alpha.13",
"typescript": "5.8.2"
},
"devDependencies": {
"@repo/eslint-config": "workspace:_",
"@repo/typescript-config": "workspace:_",
"@types/node": "^22.13.10",
"@types/react": "19.0.10",
"@types/react-dom": "19.0.4",
"eslint": "^9.22.0",
"typescript": "5.8.2"
}
}
