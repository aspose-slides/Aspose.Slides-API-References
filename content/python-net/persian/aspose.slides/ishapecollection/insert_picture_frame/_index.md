---
title: insert_picture_frame method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
یک فریم تصویر جدید که شامل تصویر مشخص‌شده است ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در ایندکس مشخص‌شده وارد می‌سازد.

### بازگرداندن
[`IPictureFrame`](/slides/python-net/fa/aspose.slides/ipictureframe) جدید ایجاد شده.

```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | شاخص صفر مبنا که فریم تصویر در آن اضافه می‌شود. |
| shape_type | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) | نوع شکل موجود در [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) را مشخص می‌کند،<br/><br/>            به‌جز تمام انواع خطوط:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | مختصات x فریم تصویر، بر حسب نقطه. |
| y | **float** | مختصات y فریم تصویر، بر حسب نقطه. |
| width | **float** | عرض فریم تصویر، بر حسب نقطه. |
| height | **float** | ارتفاع فریم تصویر، بر حسب نقطه. |
| image | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) برای نمایش در فریم تصویر. |

### موارد مرتبط
* کلاس [`IPictureFrame`](/slides/python-net/fa/aspose.slides/ipictureframe)
* کلاس [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage)
* کلاس [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* شمارشی [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)