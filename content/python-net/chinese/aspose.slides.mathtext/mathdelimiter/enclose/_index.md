---
title: enclose method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
在括号中包含数学元素

### 返回值

类型为 [`IMathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/imathdelimiter) 的数学元素，包括括号



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
在指定字符中包含数学元素，例如括号或其他字符作为框架

### 返回值

如果 `beginning_character` 和 `ending_character` 为 None， 
            对应属性仅被赋值，不会创建新对象（返回此实例）。
            否则，返回类型为 Delimiter 的新数学元素，其中包含指定字符作为框架 
            并且此 [`MathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter) 实例被框在其中。



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| beginning_character | **char** | 起始字符（通常为左括号） |
| ending_character | **char** | 结束字符（通常为右括号） |



### 另见
* class [`IMathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/imathdelimiter)
* class [`MathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter)
* module [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)