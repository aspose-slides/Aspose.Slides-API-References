---
title: Hyperlink constructor
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
创建一个超链接的实例。

```python
def __init__(self, url):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| url | **str** | Hyperlink URL. |

## __init__(self, slide) {#islide}
创建一个指向特定幻灯片的超链接实例。  
注意：创建的超链接应分配给同一演示文稿中的某个对象，否则链接将保存为 NoAction。

```python
def __init__(self, slide):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 目标幻灯片。 |

## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
使用另一个超链接作为来源创建超链接实例，覆盖次要属性。

```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/zh/aspose.slides/hyperlink) | 源超链接 |
| target_frame | **str** | 目标帧 |
| tooltip | **str** | 工具提示文本 |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |

### 另请参阅
* 类 [`Hyperlink`](/slides/python-net/zh/aspose.slides/hyperlink)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)