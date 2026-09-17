---
title: insert_picture_frame method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
يقوم بإنشاء إطار صورة جديد يحتوي على الصورة المحددة ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

### إرجاع
الـ[`IPictureFrame`](/slides/python-net/ar/aspose.slides/ipictureframe) المُنشأ حديثًا.

```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | المؤشر الصفري الذي يتم عنده إدراج إطار الصورة. |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | يحدد نوع الشكل الموجود في [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)،<br/><br/>            باستثناء جميع أنواع الخطوط:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | الإحداثي السيني لإطار الصورة، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الصورة، بالنقاط. |
| width | **float** | عرض إطار الصورة، بالنقاط. |
| height | **float** | ارتفاع إطار الصورة، بالنقاط. |
| image | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | ال[`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) لعرضه في إطار الصورة. |

### أنظر أيضًا
* الفئة [`IPictureFrame`](/slides/python-net/ar/aspose.slides/ipictureframe)
* الفئة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* الفئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* التعداد [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)