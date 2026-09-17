---
title: add_picture_frame method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
创建一个包含指定图像的新图片框，并将其添加到形状集合的末尾。

### 返回值

新创建的[`IPictureFrame`](/slides/python-net/zh/aspose.slides/ipictureframe)。

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype) | 指定 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype) 中包含的形状类型，<br/><br/>            但不包括所有类型的线：<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | 图片框的 x 坐标，单位为点。 |
| y | **float** | 图片框的 y 坐标，单位为点。 |
| width | **float** | 图片框的宽度，单位为点。 |
| height | **float** | 图片框的高度，单位为点。 |
| image | [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage) | 要在图片框中显示的[`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage)。 |

### 另请参见
* 类 [`IPictureFrame`](/slides/python-net/zh/aspose.slides/ipictureframe)
* 类 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 枚举 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)