
# Project Bisheng
<div align=center><img src="./assets/logo.png"/></div>

> '毕昇' - 中英文混排工具
>  
> 因为仅中文使用者会有这样排版需求, ~~并且我不相信 非母语中文的人 会用这玩意😄~~, 因此我懒得翻译了


## TL'DR

### CLI

```sh
npx bisheng-formatter-core {YourFile.md}
```

### API

```js
import { bishengFormat } from "bisheng-formatter-core";
const formattedContent = bishengFormat(str)
console.log(formattedContent);
```

## 功能演示

* [网页版-格式化演示](https://project-bisheng.vercel.app/)

## 组件

这个项目包含以下部分:

* [Core](https://github.com/szhshp/ProjectBisheng/tree/main/core)
* [VSC Extension](https://github.com/szhshp/ProjectBisheng/tree/main/vscode-extension)
* [Deno Package](https://github.com/szhshp/ProjectBisheng/tree/main/deno)

## TODO

<details>
<summary>TODO</summary>

* Common
  * [x] Main Readme
  * [x] .gitignore
  * [x] Logo
* Core & NPM
  * Node
    * [x] Option Page
    + [x] 繁体支持
    + [x] 符号与英文之间添加空格 (可选)
    + [ ] 支持英文符号替换后添加更多空格
  + NPM
    + [x] NPM Release
    + [x] NPM Release Ignore
+ Deno (Experimental)
  + [x] Main Feature
* VSC Extension
  + [x] Release VSC Market
  + [x] Ext Icon
  + [x] Hotkey
    - [ ] ~~Format on save~~
  + [x] Options
  + [x] Format Selected
  + [ ] Mac VSC Compatibility
* Web Version 
  + [ ] ~~Format on save~~
  + [ ] Options
* Chrome Extension
  + [x] Format on tab open
  + [x] Core Feature
  + [x] Configuration
    - [x] Sync Config
    - [x] Optional `font-family` 
  + [x] Logo
  + [x] Activate on load
  + [ ] Whitelist & Black List
  + [ ] Version Desc
  + [x] ReadMe
  + [ ] Release
    - [ ] Build Alpha
    - [ ] ~~Release to Google~~

</details>

## 鸣谢

* [doctor-jones](https://github.com/Leopoldthecoder/doctor-jones)
* [pangu-markdown](https://github.com/xlthu/pangu-markdown)
* [awesome-chrome-extension-boilerplate](https://github.com/tjx666/awesome-chrome-extension-boilerplate)
