---
title: add_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
创建一个新的 Zoom 框并将其添加到形状集合的末尾。

### Returns

新创建的 [`IZoomFrame`](/slides/python-net/zh/aspose.slides/izoomframe)。



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 新Zoom框的x坐标，单位为点。 |
| y | **float** | 新Zoom框的y坐标，单位为点。 |
| width | **float** | 新Zoom框的宽度，单位为点。 |
| height | **float** | 新Zoom框的高度，单位为点。 |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | Zoom框引用的[`ISlide`](/slides/python-net/zh/aspose.slides/islide)；<br/><br/>必须属于此演示文稿。 |

### Exceptions

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果引用的幻灯片不属于当前演示文稿，则抛出此异常。 |

## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
创建一个新的 Zoom 框并将其添加到形状集合的末尾。

### Returns

新创建的 [`IZoomFrame`](/slides/python-net/zh/aspose.slides/izoomframe)。



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 新Zoom框的x坐标，单位为点。 |
| y | **float** | 新Zoom框的y坐标，单位为点。 |
| width | **float** | 新Zoom框的宽度，单位为点。 |
| height | **float** | 新Zoom框的高度，单位为点。 |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | Zoom框引用的[`ISlide`](/slides/python-net/zh/aspose.slides/islide)；<br/><br/>必须属于此演示文稿。 |
| image | [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage) | 引用的幻灯片[`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage)的图像。 |

### Exceptions

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果引用的幻灯片不属于当前演示文稿，则抛出此异常。 |



### 另请参阅
* 类 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 类 [`IZoomFrame`](/slides/python-net/zh/aspose.slides/izoomframe)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)