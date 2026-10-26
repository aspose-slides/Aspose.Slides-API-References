---
title: insert_picture_frame method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
یک قاب تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص‌شده وارد می‌سد.

### بازگشت

[`IPictureFrame`](/slides/python-net/fa/aspose.slides/ipictureframe).



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس صفر-پایه‌ای که قاب تصویر در آن وارد می‌شود. |
| shape_type | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) | نوع شکل موجود در [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) را مشخص می‌کند،<br/><br/>            به‌استثنای تمام انواع خطوط:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | مختصات x قاب تصویر، به نقطه. |
| y | **float** | مختصات y قاب تصویر، به نقطه. |
| width | **float** | عرض قاب تصویر، به نقطه. |
| height | **float** | ارتفاع قاب تصویر، به نقطه. |
| image | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) برای نمایش در قاب تصویر. |



### موارد مرتبط
* class [`IPictureFrame`](/slides/python-net/fa/aspose.slides/ipictureframe)
* class [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage)
* class [`ShapeCollection`](/slides/python-net/fa/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)