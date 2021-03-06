# MarkDown 语法规则
### 标题
# 一级标题 后面跟着三个等号
这也相当于HTML里的H1
=================
## 二级标题 后面跟着三个减号
而这也相当于HTML里的H2
--------
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
总共六级标题，标准的MarkDown语法是在#号后加一个空格

### 有序列表
- 减号代表无序列表，记得加空格哟
* 星号也代表无序列表

### 无序列表
1. 有序列表直接在文字前加数字 + 空格就好了
2. 就这么简单

### 引用
> 一个大于号就可以表示引用了

### 图片与链接
插入链接与插入图片的语法很像，区别是图片前面有一个 ！ 感叹号
#### 插入链接
[百度](http://baidu.com)  
还有简单的用尖括号就行<http://baidu.com>  
还有加上标题的表示  [这是有title的连接](http://baidu.com '这是百度')，还有可引用的连接方式，定义变量，然后文档的任何地方都可以引用到
[引用的地址][hh]  
[hh]: http://baidu.com '这是引用style'
还可以这么使用引用地址:
[hh][]
#### 插入图片
![Mou icon](http://cdn.sspai.com/attachment/thumbnail/2016/01/11/48d6fd3530752da7e71d8f654d99d4564a86a_mw_320.jpg)

#### 插入邮件地址
一个邮件 <pengliang159@sohu.com> 链接，使用尖括号

#### 粗体和斜体
现在我在用**粗体** 或者两个__粗体__ 两个** 包含文字就是粗体 ** 一个*号包含就是斜体* 或者_斜体_

#### 表格
简单的表格可能是这样，记得与上一行有个回车:

Table          | this is header  | 列
-------------- | --------------  |-------
content cell   | Content cell    | 内容

如果你想，你也可以在两边给table加上线

|Table          | this is header  | cloumn |
|-------------- | --------------  |------- |
|content cell   | Content cell    | cell   |

#### 代码框
内嵌的代码使用 `代码` 包起来，代码框则是一个缩进或者4个空格

	private static void main(String[] args){
		System.out.println('使用这个符号把代码给包起来');
	}

#### 换行
在一行的结尾里输入两个或更多地空格会换行，相当于HTML里的`<br/>`标签

#### 水平线
三个星号或者下划线

#### 脚注
脚注和引用链接的方式很像。脚注有两件事组成：一个会成为标在上面数字的标记[^2]；脚注会被放在文档的结尾里，就像下面这样：
这是一个脚注。[^1],会按使用顺序自动排序[^g]
[^1]: 我就是脚注的定义
[^2]: 脚注定义2
[^g]: 排序了没

#### 删除线
使用两个波浪符前后包着
~~删除线~~

#### 栅格块
三个或者更多的```开始，以相同数量的```结束,记得要离上一行有个回车:

```
栅格块像Markdown里的代码块，只不过他们不是缩进并且依赖于开始和结束的栅格行去界定代码块
```

#### Mou 快捷键
* 开启同步预览： Shift + Cmd + I
* 开启字词计数(看右上角): Shift +Cmd + W
* 开启透明模式： Shift + Cmd + T
* Toogle Floating : Shift + Cmd + F
* Left/Right = 1/1: Cmd + 0
* Left/Right = 3/1: Cmd + +
* Left/Right = 1/3: Cmd + -
* 换写作方式：Cmd + L
* 全屏: Control + Cmd + F

#### 动作
复制HTML: Option + Cmd + C
加粗：选中文本 Cmd + B
斜体: 选中文本， Cmd + I
。。。。

#### 编辑
* 自动补全单词： Esc
* 查找: Cmd + F
* 关闭查找： Esc
