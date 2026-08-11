---
title: AddPictureFrame()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 404
url: /ar/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) طريقة

ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### المعلمات

| معلمة | النوع | الوصف |
| --- | --- | --- |
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
| x | **float** | الإحداثي السيني لإطار الصورة، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الصورة، بالنقاط. |
| width | **float** | عرض إطار الصورة، بالنقاط. |
| height | **float** | ارتفاع إطار الصورة، بالنقاط. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | ال[IPPImage](../../ippimage/) لعرضه في إطار الصورة. |

### قيمة الإرجاع

ال[IPictureFrame](../../ipictureframe/) الذي تم إنشاؤه حديثًا.

## راجع أيضًا

* تعداد [ShapeType](../../shapetype/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IPictureFrame](../../ipictureframe/)
* فئة [IPPImage](../../ippimage/)
* فئة [IShapeCollection](../)
* مساحة أسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)