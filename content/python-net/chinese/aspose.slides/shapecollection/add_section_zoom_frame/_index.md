---
title: add_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
创建一个新的 Section Zoom 框并将其添加到形状集合的末尾。

### 返回值

新创建的 [`ISectionZoomFrame`](/slides/python-net/zh/aspose.slides/isectionzoomframe)。



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 新 Section Zoom 框的 x 坐标，单位为点。 |
| y | **float** | 新 Section Zoom 框的 y 坐标，单位为点。 |
| width | **float** | 新 Section Zoom 框的宽度，单位为点。 |
| height | **float** | 新 Section Zoom 框的高度，单位为点。 |
| section | [`ISection`](/slides/python-net/zh/aspose.slides/isection) | [`ISection`](/slides/python-net/zh/aspose.slides/isection) 被 Section Zoom 框引用；<br/><br/>必须属于此演示文稿并至少包含一张幻灯片。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果引用的部分不属于当前演示文稿或不包含幻灯片，则抛出此异常。 |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
创建一个带有预定义图像的新 Section Zoom 框并将其添加到形状集合的末尾。

### 返回值

新创建的 [`ISectionZoomFrame`](/slides/python-net/zh/aspose.slides/isectionzoomframe)。



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 新 Section Zoom 框的 x 坐标，单位为点。 |
| y | **float** | 新 Section Zoom 框的 y 坐标，单位为点。 |
| width | **float** | 新 Section Zoom 框的宽度，单位为点。 |
| height | **float** | 新 Section Zoom 框的高度，单位为点。 |
| section | [`ISection`](/slides/python-net/zh/aspose.slides/isection) | [`ISection`](/slides/python-net/zh/aspose.slides/isection) 被 Section Zoom 框引用；<br/><br/>必须属于此演示文稿并至少包含一张幻灯片。 |
| image | [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage) | 在 Section Zoom 框中显示的 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage)。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果引用的部分不属于当前演示文稿或不包含幻灯片，则抛出此异常。 |



### 另请参阅
* 类 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage)
* 类 [`ISection`](/slides/python-net/zh/aspose.slides/isection)
* 类 [`ISectionZoomFrame`](/slides/python-net/zh/aspose.slides/isectionzoomframe)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)