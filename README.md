# Nuxt3学習用リポジトリ

## Versions

| name | version | memo |
|---|---|---|
| Nuxt | 3.0.0-rc.4 | 正式リリース後、update |
| Node | 16.15.1 | 最新推奨版LTS ※2022.6.27時点 |
| Yarn | 1.22.19 | |

## Setup (node_modules)

```bash
# yarn
yarn install
```

### Visual Studio Code Extensions

| name | url |
|---|---|
| Editor Config | https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig |

## Start Development Server

Start the development server on http://localhost:3000

```bash
yarn dev
```

## Creation Files

Check this page. https://v3.nuxtjs.org/api/commands/add

package.jsonにも定義ずみ。

```
    "add:component": "nuxi add component",
    "add:composable": "nuxi add composable",
    "add:layout": "nuxi add layout",
    "add:plugin": "nuxi add plugin",
    "add:page": "nuxi add page",
    "add:middleware": "nuxi add middleware",
    "add:api": "nuxi add api"
```

## Production

Build the application for production:

```bash
yarn build
```

Locally preview production build:

```bash
yarn preview
```

Checkout the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.

### Vercel ※mainマージでデプロイ走る

https://study-nuxt3.vercel.app/

### Nuxt3

Look at the [nuxt 3 documentation](https://v3.nuxtjs.org) to learn more.
