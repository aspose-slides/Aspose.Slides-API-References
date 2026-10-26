---
title: get_text_boxes_contains_text method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.util/slideutil/get_text_boxes_contains_text/
weight: 70
---
## get_text_boxes_contains_text(slide, text, check_placeholder_text) {#ibaseslide-str-bool}
返回在指定幻灯片上包含给定文本的所有文本框。

### 返回
一个包含指定文本的 [`ITextFrame`](/slides/python-net/zh/aspose.slides/itextframe) 对象数组。

```python
@staticmethod
def get_text_boxes_contains_text(slide, text, check_placeholder_text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide) | 要搜索的幻灯片。 |
| text | **str** | 在文本框中搜索的文本。 |
| check_placeholder_text | **bool** | 指示是否包含占位符文本中包含搜索文本的空文本框。 |

### 另见
* 类 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide)
* 类 [`ITextFrame`](/slides/python-net/zh/aspose.slides/itextframe)
* 类 [`SlideUtil`](/slides/python-net/zh/aspose.slides.util/slideutil)
* 模块 [`aspose.slides.util`](/slides/python-net/zh/aspose.slides.util)
* 库 [`Aspose.Slides`](/slides/python-net)