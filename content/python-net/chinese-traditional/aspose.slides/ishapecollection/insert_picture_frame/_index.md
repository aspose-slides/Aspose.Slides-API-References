---
title: insert_picture_frame method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
建立一個包含指定圖像的新圖片框，並將其插入到指定索引位置的形狀集合中。

### Returns

新建立的 [`IPictureFrame`](/slides/python-net/zh-hant/aspose.slides/ipictureframe)。

```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| 參數 | 型別 | 描述 |
| :- | :- | :- |
| index | **int** | 插入圖片框的零基索引。 |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 指定 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) 中包含的形狀類型，<br/><br/>            除所有線類型外：<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | 圖片框的 X 座標，單位為點。 |
| y | **float** | 圖片框的 Y 座標，單位為點。 |
| width | **float** | 圖片框的寬度，單位為點。 |
| height | **float** | 圖片框的高度，單位為點。 |
| image | [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) | 要在圖片框中顯示的 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)。 |

### See Also
* 類別 [`IPictureFrame`](/slides/python-net/zh-hant/aspose.slides/ipictureframe)
* 類別 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 列舉 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)