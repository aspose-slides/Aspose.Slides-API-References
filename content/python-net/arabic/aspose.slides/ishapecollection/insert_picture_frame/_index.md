---
title: insert_picture_frame method
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

### إرجاع
الـ[`IPictureFrame`](/slides/python-net/ar/aspose.slides/ipictureframe).

```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي يتم عنده إدراج إطار الصورة. |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | يحدد نوع الشكل الموجود في [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)،<br/><br/>            باستثناء جميع أنواع الخطوط:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | إحداثي x لإطار الصورة، بالنقاط. |
| y | **float** | إحداثي y لإطار الصورة، بالنقاط. |
| width | **float** | عرض إطار الصورة، بالنقاط. |
| height | **float** | ارتفاع إطار الصورة، بالنقاط. |
| image | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | الـ[`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) لعرضه في إطار الصورة. |

### انظر أيضًا
* فئة [`IPictureFrame`](/slides/python-net/ar/aspose.slides/ipictureframe)
* فئة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* فئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* تعداد [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)