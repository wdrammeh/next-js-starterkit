My Next.js starter kit project

Project inspired by [WebDevSimplified's Next E-Commerce MVP](https://github.com/WebDevSimplified/next-js-ecommerce-mvp)

# Set up (npm)

1. Create Next.js project

```
npx create next-app@latest {project-name}
npm i
```

2. Run

```
npm run dev
```

3. Prisma

[Quickstart](https://www.prisma.io/docs/getting-started/quickstart)

```
npm i ts-node --save-dev
npm i prisma --save-dev
npx prisma init --datasource-provider {provider}
npx prisma migrate {db} --name {tag}
```

4. shadcn/ui

[Docs](https://ui.shadcn.com/docs/installation/next)

- `npx shadcn-ui@latest init`

5. Stripe

[Install Stripe CLI](https://docs.stripe.com/stripe-cli)

```
stripe login --interactive
stripe listen --forward-to {hookUrl}
```
