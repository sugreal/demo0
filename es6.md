1.ECMAScript 6简介
大致了解了ES6，并安装了Babel等相关插件


2.let 和 const 命令
let和var很相像，但是let只能在代码块内起效
for循环还有一个特别之处
for (let i = 0; i < 3; i++) {
  let i = 'abc';
  console.log(i);
}
// abc
// abc
// abc
上面代码正确运行，输出了 3 次abc。这表明函数内部的变量i与循环变量i不在同一个作用域，有各自单独的作用域。
