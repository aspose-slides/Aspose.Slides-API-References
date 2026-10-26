---
title: add_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
创建一个新的 Section Zoom 框架并将其添加到形状集合的末尾。

### 返回值

新创建的 [`ISectionZoomFrame`](/slides/python-net/zh/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 新 Section Zoom 框架的 x 坐标，以点为单位。 |
| y | **float** | 新 Section Zoom 框架的 y 坐标，以点为单位。 |
| width | **float** | 新 Section Zoom 框架的宽度，以点为单位。 |
| height | **float** | 新 Section Zoom 框架的高度，以点为单位。 |
| section | [`ISection`](/slides/python-net/zh/aspose.slides/isection) | Section Zoom 框架引用的 [`ISection`](/slides/python-net/zh/aspose.slides/isection)；<br/><br/>必须属于此演示文稿并至少包含一张幻灯片。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果引用的节不属于当前演示文稿或不包含任何幻灯片，则会抛出此异常。 |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
创建一个带有预定义图像的新 Section Zoom 框架，并将其添加到形状集合的末尾。

### 返回值

新创建的 [`ISectionZoomFrame`](/slides/python-net/zh/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 新 Section Zoom 框架的 x 坐标，以点为单位。 |
| y | **float** | 新 Section Zoom 框架的 y 坐标，以点为单位。 |
| width | **float** | 新 Section Zoom 框架的宽度，以点为单位。 |
| height | **float** | 新 Section Zoom 框架的高度，以点为单位。 |
| section | [`ISection`](/slides/python-net/zh/aspose.slides/isection) | Section Zoom 框架引用的 [`ISection`](/slides/python-net/zh/aspose.slides/isection)；<br/><br/>必须属于此演示文稿并至少包含一张幻灯片。 |
| image | [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage) | 在 Section Zoom 框架中显示的 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage)。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果引用的节不属于当前演示文稿或不包含任何幻灯片，则会抛出此异常。 |



### 另见
* 类 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage)
* 类 [`ISection`](/slides/python-net/zh/aspose.slides/isection)
* 类 [`ISectionZoomFrame`](/slides/python-net/zh/aspose.slides/isectionzoomframe)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)