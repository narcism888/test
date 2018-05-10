README
==========================
GitHub的markdown语法在标准的markdown语法基础上做了扩充，称之为`GitHub Flavored Markdown`。简称`GFM`，GFM的基本语法
*************

|Author|narcism|
|---|---
|E-mail|narcism@qq.com

****
# markdown语法学习
## 1.段落语法学习
markdown 支持两种标题的语法，Setext 和 atx 形式。
### 1.1Setext 形式
Setext 形式是用底线的形式，利用 = （最高阶标题）和 - （第二阶标题）
****
第一章 A
=================
第一节 a
-----------------
第二节 b
-----------------
### 1.2atx形式
> Atx 形式在行首插入 # 即可，同理可以增加二级标题、三级标题、四级标题、五级标题和六级标题，总共六级，只需要增加  # 即可，标题字号相应降低
 *****
 ## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题 
# 2代码块
>区块引用则使用 email 形式的 '>' 角括号。
测试代码块

> Markdown 支持两种标题的语法，Setext 和 atx 形式
> Markdown 支持两种标题的语法，Setext 和 atx 形式
> Markdown 支持两种标题的语法，Setext 和 atx 形式 
# 3修辞和强调
>他是最可爱的人*雷锋*（斜体）
>他是最可爱的人_雷锋_ （斜体）
>他是最可爱的人**雷锋**（加粗）
>他是最可爱的人 __雷锋__（加粗）
>
# 4.列表
## 4.1无序列表（用*，+，-）
> *号
* apple
* banana
> 减号
- 苹果
- 香蕉
> 加号
+ **applei**
+ dsaf
## 4.2有序列表
>有序的列表则是使用一般的数字接着一个英文句点作为项目标记（.与内容之间加空格）
1. hong
2. lan
3. lu

# 5链接和图片
>Markdown 支援两种形式的链接和图片语法： 行内 和 参考 两种形式，两种都是使用角括号来把文字转成连结。
## 5.1行内形式
>行内形式是直接在后面用括号直接接上链接
### 5.1.1 网址
[个人博客hello](https://narcism888.github.io/)
### 5.1.2 图片
![图片](http://www.astiron.com/data/upload/image/201506/7748386409f3a7206cb4d7dfa24c78ce.jpg)
## 5.2参考形式
>参考形式的链接让你可以为链接定一个名称，之后你可以在文件的其他地方定义该链接的
### 5.2.1 网址
[百度] [1] or [个人博客hello] [2]
### 5.2.2 图片
![图片] [3]

##　6表格
>
|姓名|所在地|产品|
| ----|----|----|
|雷军|北京 |小米手机|
|老罗|北京|锤子手机|
|任正非|深圳|华为手机|
|任正非|深圳|[3]|
------------
[1]: http://baidu.com/ "百度"
[2]: https://narcism888.github.io/ "个人博客hello"
[3]: http://www.astiron.com/data/upload/image/201506/7748386409f3a7206cb4d7dfa24c78ce.jpg
