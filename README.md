# Jazz Stack 🎷

This is the Jazz Stack. This is my personal stack that I use as a basis for getting an idea up and running quickly.

It is a combination of the following technologies:

- [NextJS](https://nextjs.org/) - React Framework
- [TailwindCSS](https://tailwindcss.com/) - CSS Framework
- [TypeScript](https://www.typescriptlang.org/) - Typed JavaScript
- [Prisma](https://www.prisma.io/) - ORM
- [Clerk](https://clerk.dev/) - Authentication
- [Zod](https://zod.dev/) - Schema Validation
- [shadcn/ui](https://ui.shadcn.com/) - UI Components
- [React Hook Form](https://react-hook-form.com/) - Form Validation
- [React Table](https://react-table.tanstack.com/) - Table Library

## Getting Started

Clone this repo and run pnpm install to install all dependencies.

```bash
git clone

pnpm install
```

This is an opinionated stack. I have included Clerk as the authentication library because of its developer experience and ease of
use. I also include shadcn/ui for the same reasons. Make sure to populate the `.env` file with your Clerk API keys and database connection string. You can find the Clerk API keys in the Clerk dashboard.

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY='pk_test_....'
CLERK_SECRET_KEY='sk_test_....'

DATABASE_URL='connection string here'

```

While opinionated, I don't provide any opinions on choice of database or hosting. I personally use [Vercel](https://vercel.com/) and [PlanetScale](https://planetscale.com/) for hosting and database respectively.

Created by [Ras Fincher](https://rhymeswithjazz.com)
