---
title: add_picture_frame method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
建立一個包含指定影像的新圖片框架，並將其加入形狀集合的末端。

### Returns
新建立的 [`IPictureFrame`](/slides/python-net/zh-hant/aspose.slides/ipictureframe)。

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 指定 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) 中所包含的形狀類型，<br/><br/>除所有線條類型外：<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | 圖片框架的 x 坐標，以點為單位。 |
| y | **float** | 圖片框架的 y 坐標，以點為單位。 |
| width | **float** | 圖片框架的寬度，以點為單位。 |
| height | **float** | 圖片框架的高度，以點為單位。 |
| image | [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) | 要在圖片框架中顯示的 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)。 |

### 另請參閱
* 類別 [`IPictureFrame`](/slides/python-net/zh-hant/aspose.slides/ipictureframe)
* 類別 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 列舉 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)