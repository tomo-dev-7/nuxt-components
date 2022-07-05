# pj-nuxt-components

## npx create-nuxt-app {name} 実行後の作業

### ディレクトリ整理

1. 新規ディレクトリ作成し、src 配下に集約

- src
  - middleware
  - plugins
  - layouts

以下コマンド実行
`mkdir -p src2/{plugins,middleware,layouts} && mv assets components pages static store src/`

1. `nuxt.config.js` に追記

```
srcDir: './src',
```
