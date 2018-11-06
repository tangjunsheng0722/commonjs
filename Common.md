# Commonjs
## 什么是commonjs
> 一套为了javascript模块化开发的语法规范
## 为什么制定commonjs规范
> 在后端，JavaScript的规范远远落后并且有很多缺陷，这使得难以使用JavaScript开发大型应用。比如：
```
没有模块系统
标准库较少
没有标准接口
缺乏包管理系统
列表内容
```
## CommonJS模块规范
> CommonJS模块规范主要分为三部分：

> 模块引用
```
var math=require（'math');
```
> 模块定义
```
exports.add=function (num1,num2){
    alert(num1+num2);
}
```
> 模块标识 ：模块标识指的是传递给require方法的参数，必须是符合小驼峰命名的字符串，或者以 . 、.. 、开头的相对路径，或者绝对路径
## CommonJS模块规范的好处
```
CommonJS模块规范很好地解决变量污染问题，每个模块具有独立空间，互不干扰，命名空间等方案与之相比相形见绌。
CommonJS规范定义模块十分简单，接口十分简洁。
CommonJS模块规范支持引入和导出功能，这样可以顺畅地连接各个模块，实现彼此间的依赖关系。
```
## 体现
> Node.js