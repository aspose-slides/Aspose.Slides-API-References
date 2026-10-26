---
title: add_picture_frame method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
ينشئ إطار صور جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال.

### إرجاع
الكائن المُنشأ حديثًا [`IPictureFrame`](/slides/python-net/ar/aspose.slides/ipictureframe).

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | يحدد نوع الشكل الموجود في [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)،<br/><br/>            باستثناء جميع أنواع الخطوط:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | الإحداثي السيني لإطار الصورة، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الصورة، بالنقاط. |
| width | **float** | العرض لإطار الصورة، بالنقاط. |
| height | **float** | الارتفاع لإطار الصورة، بالنقاط. |
| image | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | ال[`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) لعرضه في إطار الصورة. |

### انظر أيضًا
* الفئة [`IPictureFrame`](/slides/python-net/ar/aspose.slides/ipictureframe)
* الفئة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* الفئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* التعداد [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)