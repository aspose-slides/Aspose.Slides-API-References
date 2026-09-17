---
title: insert_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
创建一个新 Zoom 框，并将其插入到指定索引的形状集合中。

### 返回值

新创建的[`IZoomFrame`](/slides/python-net/zh/aspose.slides/izoomframe)。



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入 Zoom 框的零基索引。 |
| x | **float** | 新 Zoom 框的 x 坐标，单位为点。 |
| y | **float** | 新 Zoom 框的 y 坐标，单位为点。 |
| width | **float** | 新 Zoom 框的宽度，单位为点。 |
| height | **float** | 新 Zoom 框的高度，单位为点。 |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | Zoom 框引用的[`ISlide`](/slides/python-net/zh/aspose.slides/islide)。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果引用的 slide 不属于当前演示文稿，则抛出此异常。 |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
创建一个带预定义图像的新 Zoom 框，并将其插入到指定索引的形状集合中。

### 返回值

新创建的[`IZoomFrame`](/slides/python-net/zh/aspose.slides/izoomframe)。



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入 Zoom 框的零基索引。 |
| x | **float** | 新 Zoom 框的 x 坐标，单位为点。 |
| y | **float** | 新 Zoom 框的 y 坐标，单位为点。 |
| width | **float** | 新 Zoom 框的宽度，单位为点。 |
| height | **float** | 新 Zoom 框的高度，单位为点。 |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | Zoom 框引用的[`ISlide`](/slides/python-net/zh/aspose.slides/islide)。 |
| image | [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage) | 引用的 slide [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage) 的图像。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果引用的 slide 不属于当前演示文稿，则抛出此异常。 |



### 另请参见
* 类 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 类 [`IZoomFrame`](/slides/python-net/zh/aspose.slides/izoomframe)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)