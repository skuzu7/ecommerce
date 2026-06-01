# E-commerce

A modern, internationalized e-commerce storefront built with Next.js.

## Features

- **Internationalization** (multi-language) via `next-intl`
- **Product catalog** with cart state managed through React Context
- **Accessible UI** built on Radix UI primitives (shadcn-style components)
- Toast notifications and smooth animations

## Tech stack

- **Framework:** Next.js (App Router) + TypeScript
- **Styling:** Tailwind CSS + class-variance-authority
- **UI:** Radix UI (dialog, navigation-menu, select, accordion, etc.)
- **i18n:** next-intl
- **Animation:** Framer Motion
- **Notifications:** sonner

## Getting started

```bash
npm install
npm run dev      # http://localhost:3000
```

## Project structure

```
src/
  app/[locale]/  localized routes
  components/     UI components
  context/        cart / global state
  messages/       i18n translation files
  i18n.ts         i18n config
  middleware.ts   locale routing
```