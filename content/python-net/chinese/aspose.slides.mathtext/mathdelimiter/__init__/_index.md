---
title: MathDelimiter constructor
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathdelimiter/__init__/
weight: 10
---
## __init__(self, element) {#imathelement}
使用指定的 element 作为唯一的基元素来初始化 MathDelimiter


```python
def __init__(self, element):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| element | [`IMathElement`](/slides/python-net/zh/aspose.slides.mathtext/imathelement) | 应用分隔符的基 element。可以为 None。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当 `element` 是其他元素（例如 MathBlock）的容器时抛出此错误。在这种情况下，需要使用 IEnumerable 参数调用不同的构造函数。 |



### 另请参阅
* 类 [`IMathElement`](/slides/python-net/zh/aspose.slides.mathtext/imathelement)
* 类 [`MathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)