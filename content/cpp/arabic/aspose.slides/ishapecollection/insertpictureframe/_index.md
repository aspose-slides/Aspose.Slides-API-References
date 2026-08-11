---
title: InsertPictureFrame()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.
type: docs
weight: 417
url: /ar/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) طريقة

ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يتم عنده إدراج إطار الصورة. |
| shapeType | [ShapeType](../../shapetype/) | يحدد نوع الشكل الموجود في [ShapeType](../../shapetype/)، باستثناء جميع أنواع الخطوط:

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | إحداثي x لإطار الصورة، بالنقاط. |
| y | **float** | إحداثي y لإطار الصورة، بالنقاط. |
| width | **float** | عرض إطار الصورة، بالنقاط. |
| height | **float** | ارتفاع إطار الصورة، بالنقاط. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) لعرضه في إطار الصورة. |

### قيمة الإرجاع

الـ[IPictureFrame](../../ipictureframe/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)