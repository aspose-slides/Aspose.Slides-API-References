---
title: insert_picture_frame method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
建立一個包含指定圖像的新圖片框，並將其插入至指定索引的形狀集合中。

### 返回值

新建立的 [`IPictureFrame`](/slides/python-net/zh-hant/aspose.slides/ipictureframe).



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```


| 參數 | 型別 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入圖片框的零基索引。 |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 指定 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) 中包含的形狀類型，<br/><br/>            除了所有類型的線條：<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | 圖片框的 x 座標（單位：點）。 |
| y | **float** | 圖片框的 y 座標（單位：點）。 |
| width | **float** | 圖片框的寬度（單位：點）。 |
| height | **float** | 圖片框的高度（單位：點）。 |
| image | [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) | 用於在圖片框中顯示的 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)。 |



### 參見
* 類別 [`IPictureFrame`](/slides/python-net/zh-hant/aspose.slides/ipictureframe)
* 類別 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 列舉 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)