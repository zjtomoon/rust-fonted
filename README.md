# rust-fronted

## tauri

### 1. Start a New Tauri Project[​](https://tauri.studio/docs/getting-started/beginning-tutorial#1-start-a-new-tauri-project "Direct link to heading")

```
npx create tauri-app
```

### Run and compile project

```bash
npm run tauri help
npm run tauri dev
npm run tauri build
```

## webassembly

+ 1、克隆模板

```bash
    cargo generate --git https://github.com/rustwasm/wasm-pack-template
```

+ 2、wasm-pack编译

```bash
    wasm-pack build
```

+ 3、部署到web

```bash
    npm init wasm-app www
```

+ 4、安装node_modules

```bash
    npm install
```

+ 5、dev运行

```bash
    npm run start
```

+ 6、编译web项目

```bash
    npm run build
```
