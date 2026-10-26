---
title: add_picture_frame method
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
يقوم بإنشاء إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية الـ
            مجموعة الأشكال.

### الإرجاع
الـ [`IPictureFrame`](/slides/python-net/ar/aspose.slides/ipictureframe) الذي تم إنشاؤه حديثًا.

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | يحدد نوع الشكل الموجود في [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)،<br/><br/>            باستثناء جميع أنواع الخطوط:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | الإحداثي السيني لإطار الصورة، بوحدات النقاط. |
| y | **float** | الإحداثي الصادي لإطار الصورة، بوحدات النقاط. |
| width | **float** | عرض إطار الصورة، بوحدات النقاط. |
| height | **float** | ارتفاع إطار الصورة، بوحدات النقاط. |
| image | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) التي سيتم عرضها في إطار الصورة. |

### أنظر أيضًا
* الفئة [`IPictureFrame`](/slides/python-net/ar/aspose.slides/ipictureframe)
* الفئة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* الفئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* التعداد [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)