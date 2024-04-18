# vue.vn
This is the code repository for Learning Vue.js

## Add Vue

Let me tell you that there are four ways to add Vue to your project.

1. CDN Package
2. npm
3. Vue CLI
4. Vite

### CDN Package

```html
<script src="https://unpkg.com/vue@next"></script>
# OR
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.min.js"></script>
```

To Run The Project

[Live Server](https://github.com/tapio/live-server)
```
npm install -g live-server
live-server .
```

[Serve](https://github.com/vercel/serve)
```
npm install -g serve
# -s flag means serve it in Single-Page Application mode
# which deals with the routing problem below
serve -s dist
```

### npm

```
npm install vue@next

npm install -g pnpm

npm install -g yarn
npm upgrade -g yarn
yarn version check

npm install -g bun
bun upgrade

npm create vue@latest
pnpm create vue@latest
yarn create vue@latest
bun create vue@latest

cd <your-project-name>
npm install
npm run format
npm run dev
npm run build

pnpm install
pnpm format
pnpm dev
pnpm build

yarn
yarn dev
yarn build

bun install
bun run dev
bun run build
```

### Vue CLI

To Install Vue Globally

```
npm install -g vue-cli
# OR
npm install -g @vue/cli
# OR
yarn global add @vue/cli
```

To Create a Project

```
vue create <your-project-name>
vue create hello-world
# OR
vue ui
```

To Run The Project

```
cd <your-project-name>
cd hello-world

npm run serve
```

### Vite

```
npm create vite@latest
pnpm create vite
yarn create vite
bun create vite

npm init vite
npm init vite-app <project-name>
# OR
yarn create vite

npm install
npm run dev
npm run build
```

vite-pnpm