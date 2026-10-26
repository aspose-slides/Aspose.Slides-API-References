---
title: enclose method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
将数学元素用括号括起来

### 返回

类型为 [`IMathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/imathdelimiter) 的数学元素，包含括号



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
在指定字符（如括号或其他字符）中封装此块的子元素作为框架

### 返回

类型为 [`IMathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/imathdelimiter) 的数学元素，包含指定字符作为框架



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| beginning_character | **char** | 开始字符（通常为左括号） |
| ending_character | **char** | 结束字符（通常为右括号） |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
在指定字符（如括号或其他字符）中封装此块的子元素作为框架，并使用分隔符字符进行分隔

### 返回

类型为 [`IMathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/imathdelimiter) 的数学元素，包含指定字符作为框架并作为分隔符



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| beginning_character | **char** | 开始字符（通常为左括号） |
| ending_character | **char** | 结束字符（通常为右括号） |
| separator_character | **char** | 分隔符字符 |



### 参见
* 类 [`IMathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/imathdelimiter)
* 类 [`MathBlock`](/slides/python-net/zh/aspose.slides.mathtext/mathblock)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)