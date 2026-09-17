---
title: enclose method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/imathblock/enclose/
weight: 90
---
## enclose(self) {#}



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| beginning_character | **char** |  |
| ending_character | **char** |  |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
将此块的子元素用指定字符（例如括号或其他字符）包裹并使用分隔符字符进行分隔

### 返回

类型为 [`IMathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/imathdelimiter) 的数学元素，包含指定字符作为框架和分隔符



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| beginning_character | **char** | 开始字符（通常为左括号） |
| ending_character | **char** | 结束字符（通常为右括号） |
| separator_character | **char** | 分隔符字符 |



### 另请参阅
* 类 [`IMathBlock`](/slides/python-net/zh/aspose.slides.mathtext/imathblock)
* 类 [`IMathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/imathdelimiter)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)