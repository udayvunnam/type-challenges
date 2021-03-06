<!--info-header-start--><h1>科里化 1 <img src="https://img.shields.io/badge/-%E5%9B%B0%E9%9A%BE-red" alt="困难"/> <img src="https://img.shields.io/badge/-%23array-999" alt="#array"/> <img src="https://img.shields.io/badge/-%234.0-999" alt="#4.0"/></h1><blockquote><p>by Anthony Fu <a href="https://github.com/antfu" target="_blank">@antfu</a></p></blockquote><p><a href="https://tsch.js.org/17/play/zh-CN" target="_blank"><img src="https://img.shields.io/badge/-%E6%8E%A5%E5%8F%97%E6%8C%91%E6%88%98-3178c6?logo=typescript" alt="接受挑战"/></a> &nbsp;&nbsp;&nbsp;<a href="./README.md" target="_blank"><img src="https://img.shields.io/badge/-English-gray" alt="English"/></a> </p><!--info-header-end-->

> 由谷歌自动翻译，欢迎 PR 改进翻译质量。

>在此挑战中建议使用TypeScript 4.0

[Currying]（https://en.wikipedia.org/wiki/Currying）是一种将带有多个参数的函数转换为每个带有一个参数的函数序列的技术。

例如：

```ts
const add = (a: number, b: number) => a + b
const three = add(1, 2)

const curriedAdd = Currying(add)
const five = curriedAdd(2)(3)
```

传递给`Currying`的函数可能有多个参数，您需要正确键入它。

在此挑战中，curried函数一次仅接受一个参数。分配完所有参数后，它应返回其结果。

<!--info-footer-start--><br><a href="../../README.zh-CN.md" target="_blank"><img src="https://img.shields.io/badge/-%E8%BF%94%E5%9B%9E%E9%A6%96%E9%A1%B5-grey" alt="返回首页"/></a> <a href="https://tsch.js.org/17/answer/zh-CN" target="_blank"><img src="https://img.shields.io/badge/-%E5%88%86%E4%BA%AB%E4%BD%A0%E7%9A%84%E8%A7%A3%E7%AD%94-teal" alt="分享你的解答"/></a> <a href="https://tsch.js.org/17/solutions" target="_blank"><img src="https://img.shields.io/badge/-%E6%9F%A5%E7%9C%8B%E8%A7%A3%E7%AD%94-de5a77?logo=awesome-lists&logoColor=white" alt="查看解答"/></a> <hr><h3>相关挑战</h3><a href="https://github.com/type-challenges/type-challenges/tree/master/questions/14-easy-first/README.zh-CN.md" target="_blank"><img src="https://img.shields.io/badge/-14%E3%83%BB%E7%AC%AC%E4%B8%80%E4%B8%AA%E5%85%83%E7%B4%A0-90bb12" alt="14・第一个元素"/></a>  <a href="https://github.com/type-challenges/type-challenges/tree/master/questions/16-medium-pop/README.zh-CN.md" target="_blank"><img src="https://img.shields.io/badge/-16%E3%83%BB%E5%87%BA%E5%A0%86-eaa648" alt="16・出堆"/></a> <!--info-footer-end-->