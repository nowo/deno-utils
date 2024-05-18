# 简介

一个简单的工具函数库

- wait：延迟调用方法
- deepClone：数据深拷贝方法
- getFileType：判断文件类型

## Install

```sh
# deno
deno add @nowo/utils
```

```sh
# npm
npx jsr add @nowo/utils
```

## Usage

```ts
import { wait, deepClone, getFileType } from "@nowo/utils";

await wait(1000);
console.log('aaa');  // 1秒之后打印 aaa

deepClone({ id: 1 })  // { id: 1 }

getFileType(`132546.png`)  // 'image'
```

## Docs

- [API docs](https://jsr.io/@nowo/utils/doc)
