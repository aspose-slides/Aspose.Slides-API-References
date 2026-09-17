---
title: find_and_replace_text method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.util/slideutil/find_and_replace_text/
weight: 20
---
## find_and_replace_text(presentation, with_masters, find, replace, format) {#ipresentation-bool-str-str-portionformat}
在演示文稿中查找并替换文本，并使用给定的格式


```python
@staticmethod
def find_and_replace_text(presentation, with_masters, find, replace, format):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) | 已扫描的演示文稿。 |
| with_masters | **bool** | 确定是否应扫描母版幻灯片。 |
| find | **str** | 要查找的字符串值。 |
| replace | **str** | 要替换的字符串值。 |
| format | [`PortionFormat`](/slides/python-net/zh/aspose.slides/portionformat) | 用于替换文本段的格式。如果为 None，则将使用找到的字符串的第一个 <br/><br/>            字符的格式。 |



### 另请参见
* 类 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)
* 类 [`PortionFormat`](/slides/python-net/zh/aspose.slides/portionformat)
* 类 [`SlideUtil`](/slides/python-net/zh/aspose.slides.util/slideutil)
* 模块 [`aspose.slides.util`](/slides/python-net/zh/aspose.slides.util)
* 库 [`Aspose.Slides`](/slides/python-net)