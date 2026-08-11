---
title: AddPictureFrame()
second_title: مرجع API Aspose.Slides للـ C++
description: ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 443
url: /ar/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) طريقة

ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### الوسائط

| المعامل | النوع | الوصف |
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
| x | **float** | الإحداثي السيني لإطار الصورة، بوحدات النقاط. |
| y | **float** | الإحداثي الصادي لإطار الصورة، بوحدات النقاط. |
| width | **float** | عرض إطار الصورة، بوحدات النقاط. |
| height | **float** | ارتفاع إطار الصورة، بوحدات النقاط. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | ال[IPPImage](../../ippimage/) لعرضه في إطار الصورة. |

### قيمة الإرجاع

ال[IPictureFrame](../../ipictureframe/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IPictureFrame](../../ipictureframe/)
* فئة [IPPImage](../../ippimage/)
* فئة [ShapeCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)