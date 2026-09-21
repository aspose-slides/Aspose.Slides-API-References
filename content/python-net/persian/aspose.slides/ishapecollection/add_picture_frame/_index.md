---
title: add_picture_frame method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
یک فریم تصویر جدید شامل تصویر مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

### بازگشت

شیء جدید ایجاد شده [`IPictureFrame`](/slides/python-net/fa/aspose.slides/ipictureframe).

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
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
* enumeration [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)