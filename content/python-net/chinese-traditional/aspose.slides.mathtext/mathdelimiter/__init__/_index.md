---
title: MathDelimiter constructor
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/__init__/
weight: 10
---
## __init__(self, element) {#imathelement}
使用指定的 element 作為單一基礎參數來初始化 MathDelimiter

```python
def __init__(self, element):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| element | [`IMathElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathelement) | 套用分隔符號的基礎元素。可以是 None。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當 `element` 是其他元素的容器，例如 MathBlock 時拋出。在此情況下，您需要使用 IEnumerable 參數呼叫不同的建構函式。 |

### 另見
* 類別 [`IMathElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathelement)
* 類別 [`MathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 程式庫 [`Aspose.Slides`](/slides/python-net)