# Tutorial: How to set up React, webpack, and Babel 7 from scratch (2020)

照著這篇做的一些筆記就直接寫在 README

- <https://www.valentinog.com/blog/babel/>

## `$_`

``` sh
mkdir webpack-react-tutorial && cd $_
```

`$_` 可以自動解開前一項指令最後一項元素的內容。這樣寫在建立資料夾之後就可以比較便利的切換到該資料夾。

參考： <https://unix.stackexchange.com/a/271693>

## npm -> yarn 相關

### 安裝相依

``` sh
yarn install
```

### 跳過初始設定直接建立一個空的 package.json

| npm | yarn |
|---|---|
| `npm init -y` | `yarn init -y` |

- <https://docs.npmjs.com/cli/init>
- <https://legacy.yarnpkg.com/en/docs/cli/init/#toc-yarn-init-yes-y>

### 加入開發時的相依

| npm | yarn |
|---|---|
| `npm i <dependency> --dev` | `yarn add <dependency> --dev` |

- <https://docs.npmjs.com/cli/install>
- <https://legacy.yarnpkg.com/en/docs/cli/add/#toc-yarn-add-dev-d>

## Markdown rules

因為 Visual Studio Code 有加 markdown-lint ，碰到的問題也一併寫在這。

### No Bare URLs

因為有些轉換器無法直接轉換 URL ，因此有建議應該要用小於大於箭頭包起來。

- <https://github.com/updownpress/markdown-lint/blob/master/rules/034-no-bare-urls.md>

## Libraries

- webpack
- webpack-cli
