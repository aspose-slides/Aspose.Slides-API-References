---
title: insert_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
创建一个新的 Zoom 框并将其插入到指定索引的形状集合中。

### Returns

新创建的 [`IZoomFrame`](/slides/python-net/zh/aspose.slides/izoomframe)。



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入 Zoom 框的零基索引。 |
| x | **float** | 新 Zoom 框的 x 坐标（单位：点）。 |
| y | **float** | 新 Zoom 框的 y 坐标（单位：点）。 |
| width | **float** | 新 Zoom 框的宽度（单位：点）。 |
| height | **float** | 新 Zoom 框的高度（单位：点）。 |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | Zoom 框引用的 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)。 |

### Exceptions

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果引用的幻灯片不属于当前演示文稿，则抛出此异常。 |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
创建一个带有预定义图像的新 Zoom 框并将其插入到指定索引的形状集合中。

### Returns

新创建的 [`IZoomFrame`](/slides/python-net/zh/aspose.slides/izoomframe)。



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入 Zoom 框的零基索引。 |
| x | **float** | 新 Zoom 框的 x 坐标（单位：点）。 |
| y | **float** | 新 Zoom 框的 y 坐标（单位：点）。 |
| width | **float** | 新 Zoom 框的宽度（单位：点）。 |
| height | **float** | 新 Zoom 框的高度（单位：点）。 |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | Zoom 框引用的 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)。 |
| image | [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage) | 引用的幻灯片 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage) 的图像。 |

### Exceptions

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果引用的幻灯片不属于当前演示文稿，则抛出此异常。 |



### See Also
* 类 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 类 [`IZoomFrame`](/slides/python-net/zh/aspose.slides/izoomframe)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)