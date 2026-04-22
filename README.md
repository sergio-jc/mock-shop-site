![banner](/public/banner.png)

<p align="center">
  <img src="https://img.shields.io/badge/Astro-6-FF5D01?style=for-the-badge&logo=astro&logoColor=white" alt="Astro 6" />
  <img src="https://img.shields.io/badge/Starlight-Docs-7C3AED?style=for-the-badge" alt="Starlight Docs" />
  <img src="https://img.shields.io/badge/Galaxy%20Theme-Starlight-111827?style=for-the-badge" alt="Starlight Theme Galaxy" />
  <img src="https://img.shields.io/badge/Node.js-20-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js 20" />
  <img src="https://img.shields.io/badge/pnpm-Package%20Manager-F69220?style=for-the-badge&logo=pnpm&logoColor=white" alt="pnpm" />
</p>

# 🏬 Mock Shop Site

Static documentation site for the [Mock Shop API](https://github.com/sergio-jc/mock-shop-api) — a production-ready REST + GraphQL e-commerce API built with NestJS.

## Purpose

A lightweight public-facing page to showcase and document the Mock Shop API. Built as a companion to the API repo to provide a clean, accessible reference for endpoints, features, and usage examples.

## Tech Stack

| | |
|---|---|
| Framework | [Astro 6](https://astro.build/) |
| Docs theme | [Starlight](https://starlight.astro.build/) + [starlight-theme-galaxy](https://github.com/HiDeoo/starlight-theme-galaxy) |

## Configuration

| Variable | Default | Description |
|---|---|---|
| `BASE_API_URL` | `https://api.mockshop.dev` | Base URL of the Mock Shop API. Set this to point the site to a different deployment. |

## Getting Started

```bash
pnpm install
pnpm dev       # localhost:4321
pnpm build     # ./dist/
pnpm preview   # preview production build
```

