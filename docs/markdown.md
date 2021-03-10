# Markdown 常规语法


- - -
##分隔线

* 第一项
    > 区块嵌套

##Markdown 代码

- `printf()` 函数

或
```javascript
$(document).ready(function () {
    alert('RUNOOB');
});
```

##Markdown 链接

- 这是一个链接 [菜鸟教程](https://www.runoob.com)
- 通过变量来设置一个链接，变量赋值在文档末尾进行
- 这个链接用 1 作为网址变量 [Google][1]
- 这个链接用 runoob 作为网址变量 [Runoob][runoob]

[1]: http://www.google.com/
[runoob]: http://www.runoob.com/

##支持 HTML 元素

- <img src="http://static.runoob.com/images/runoob-logo.png" width="30%">
- 使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

**文本加粗** 

- 可用\表示转义字符
- \*\* 正常显示星号 \*\*

##Markdown 图片

- ![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png "可选标题")

##表单： 

|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |

##画流程图和公式
[用Markdown画流程图和写公式](https://www.runoob.com/markdown/md-advance.html)

##列表
- 无序列表使用星号(*)、加号(+)或是减号(-)作为列表标记
- 有序列表用1,2,3,4等

- 列表嵌套只需在子列表中的选项添加四个空格即可：
    1. 第一项：
        - 第一项嵌套的第一个元素
        - 第一项嵌套的第二个元素
    2. 第二项：
        - 第二项嵌套的第一个元素
        - 第二项嵌套的第二个元素

##其他
![logo.png](/pic/logo.png)

~~删除线~~

<u>下划线</u>