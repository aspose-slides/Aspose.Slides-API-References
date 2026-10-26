---
title: insert_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
创建一个新的 Section Zoom 框，并将其插入到形状集合中的指定索引位置。

### 返回值

新创建的 [`ISectionZoomFrame`](/slides/python-net/zh/aspose.slides/isectionzoomframe)。

```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入 Section Zoom 框的零基索引。 |
| x | **float** | 新 Section Zoom 框的 x 坐标（单位：点）。 |
| y | **float** | 新 Section Zoom 框的 y 坐标（单位：点）。 |
| width | **float** | 新 Section Zoom 框的宽度（单位：点）。 |
| height | **float** | 新 Section Zoom 框的高度（单位：点）。 |
| section | [`ISection`](/slides/python-net/zh/aspose.slides/isection) | Section Zoom 框引用的 [`ISection`](/slides/python-net/zh/aspose.slides/isection)；<br/><br/>            必须属于此演示文稿且至少包含一张幻灯片。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果引用的节不属于当前演示文稿或不包含幻灯片，则抛出此异常。 |

## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
创建一个带有预定义图像的新 Section Zoom 框，并将其插入到形状集合中的指定索引位置。

### 返回值

新创建的 [`ISectionZoomFrame`](/slides/python-net/zh/aspose.slides/isectionzoomframe)。

```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入 Section Zoom 框的零基索引。 |
| x | **float** | 新 Section Zoom 框的 x 坐标（单位：点）。 |
| y | **float** | 新 Section Zoom 框的 y 坐标（单位：点）。 |
| width | **float** | 新 Section Zoom 框的宽度（单位：点）。 |
| height | **float** | 新 Section Zoom 框的高度（单位：点）。 |
| section | [`ISection`](/slides/python-net/zh/aspose.slides/isection) | Section Zoom 框引用的 [`ISection`](/slides/python-net/zh/aspose.slides/isection)；<br/><br/>            必须属于此演示文稿且至少包含一张幻灯片。 |
| image | [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage) | 在 Section Zoom 框中显示的图像。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果引用的节不属于当前演示文稿或不包含幻灯片，则抛出此异常。 |

### 另请参阅
* 类 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage)
* 类 [`ISection`](/slides/python-net/zh/aspose.slides/isection)
* 类 [`ISectionZoomFrame`](/slides/python-net/zh/aspose.slides/isectionzoomframe)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)