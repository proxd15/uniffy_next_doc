# Next.js Starter Documentation

## Introduction to Next.js
Next.js is a powerful React framework designed for building full-stack web applications. It extends React's capabilities by providing additional features and optimizations that simplify development and enhance performance.

With Next.js, you don't have to worry about the complexities of bundling, compiling, and other configurations, as it automatically manages these tasks. This allows you to concentrate on what matters most: building your application.

## Key Features

| **Feature**      | **Description**                                                                                                                       |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| **Routing**      | A file-system-based router that supports layouts, nested routing, loading states, error handling, and more, built on top of Server Components. |
| **Rendering**    | Offers both Client-side and Server-side Rendering, optimized with Static and Dynamic Rendering on the server. Supports streaming on Edge and Node.js runtimes. |
| **Data Fetching**| Simplified data fetching using async/await in Server Components, along with an extended fetch API for request memoization, data caching, and revalidation. |
| **Styling**      | Full support for various styling methods, including CSS Modules, Tailwind CSS, and CSS-in-JS, allowing you to choose the best fit for your project. |
| **Optimizations**| Enhances Core Web Vitals and User Experience through optimizations for images, fonts, and scripts.                                      |
| **TypeScript**   | Comprehensive TypeScript support with enhanced type checking, efficient compilation, and custom TypeScript plugins.                    |

## Understanding App Router vs. Pages Router

Next.js offers two types of routers:

- **App Router:** The newer router, designed to leverage React's latest features like Server Components and Streaming, making it ideal for modern applications.
- **Pages Router:** The original Next.js router, still supported for legacy projects, offering server-rendered React applications.

## Getting Started with Next.js

### Installation

**Automatic Installation**

The easiest way to get started with Next.js is by using `create-next-app`, which automatically sets up your project. To create a new project, run:

```bash
npx create-next-app@latest
```

```bash
What is your project named? my-app
Would you like to use TypeScript? No / Yes
Would you like to use ESLint? No / Yes
Would you like to use Tailwind CSS? No / Yes
Would you like to use `src/` directory? No / Yes
Would you like to use App Router? (recommended) No / Yes
Would you like to customize the default import alias (@/*)? No / Yes
What import alias would you like configured? @/*
```

After the prompts, create-next-app will create a folder with your project name and install the required dependencies.


