---
title: InsertPictureFrame()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.
type: docs
weight: 456
url: /ar/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) طريقة

ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يُدرج عنده إطار الصورة. |
| shapeType | [ShapeType](../../shapetype/) | يحدد نوع الشكل الموجود في [ShapeType](../../shapetype/)، باستثناء جميع أنواع الخطوط:\n\n[ShapeType::Line](../../shapetype/),\n\n[ShapeType::StraightConnector1](../../shapetype/),\n\n[ShapeType::BentConnector2](../../shapetype/),\n\n[ShapeType::BentConnector3](../../shapetype/),\n\n[ShapeType::BentConnector4](../../shapetype/),\n\n[ShapeType::BentConnector5](../../shapetype/),\n\n[ShapeType::CurvedConnector2](../../shapetype/),\n\n[ShapeType::CurvedConnector3](../../shapetype/),\n\n[ShapeType::CurvedConnector4](../../shapetype/),\n\n[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | الإحداثي س لإطار الصورة، بالنقاط. |
| y | **float** | الإحداثي ص لإطار الصورة، بالنقاط. |
| width | **float** | عرض إطار الصورة، بالنقاط. |
| height | **float** | ارتفاع إطار الصورة، بالنقاط. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | الـ [IPPImage](../../ippimage/) لعرضه في إطار الصورة. |

### قيمة الإرجاع

الـ [IPictureFrame](../../ipictureframe/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* عدد [ShapeType](../../shapetype/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IPictureFrame](../../ipictureframe/)
* فئة [IPPImage](../../ippimage/)
* فئة [ShapeCollection](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)