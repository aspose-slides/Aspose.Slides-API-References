---
title: add_picture_frame method
second_title: Aspose.Slides for Python 透過 .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
建立一個包含指定圖像的新圖片框，並將其加入形狀集合的末端。

### 傳回值

新建立的 [`IPictureFrame`](/slides/python-net/zh-hant/aspose.slides/ipictureframe)。

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 指定 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) 中包含的形狀類型，<br/><br/>            除了所有線條類型：<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | 圖片框的 x 座標（單位為點）。 |
| y | **float** | 圖片框的 y 座標（單位為點）。 |
| width | **float** | 圖片框的寬度（單位為點）。 |
| height | **float** | 圖片框的高度（單位為點）。 |
| image | [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) | 顯示在圖片框中的 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)。 |

### 另請參閱
* class [`IPictureFrame`](/slides/python-net/zh-hant/aspose.slides/ipictureframe)
* class [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)
* class [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)