---
title: InsertAutoShape()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ شكلًا تلقائيًا جديدًا ويُدخله في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي.
type: docs
weight: 339
url: /ar/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) method

ينشئ شكلًا تلقائيًا جديدًا ويُدخله في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس صفر-الأساس الذي سيتم إدخال الشكل التلقائي الجديد عنده. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) للـ shape التلقائي الذي سيتم إدخاله. |
| x | **float** | الإحداثي x لإطار الشكل، بوحدات النقاط. |
| y | **float** | الإحداثي y لإطار الشكل، بوحدات النقاط. |
| width | **float** | عرض إطار الشكل، بوحدات النقاط. |
| height | **float** | ارتفاع إطار الشكل، بوحدات النقاط. |

### قيمة الإرجاع

الـ [IAutoShape](../../iautoshape/) الذي تم إنشاؤه حديثًا.

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) method

ينشئ شكلًا تلقائيًا جديدًا ويُدخله في مجموعة الأشكال عند الفهرس المحدد، مع إتاحة إمكانية تهيئته بنمط القالب الافتراضي.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس صفر-الأساس الذي سيتم إدخال الشكل التلقائي عنده. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) للـ shape التلقائي الذي سيتم إدخاله. |
| x | **float** | الإحداثي x لإطار الشكل، بوحدات النقاط. |
| y | **float** | الإحداثي y لإطار الشكل، بوحدات النقاط. |
| width | **float** | عرض إطار الشكل، بوحدات النقاط. |
| height | **float** | ارتفاع إطار الشكل، بوحدات النقاط. |
| createFromTemplate | **bool** | صحيح لتطبيق نمط القالب الافتراضي (بما في ذلك اسم غير فارغ، نمط بسيط، ونص مركزي)؛ خطأ لإنشاء الشكل مع تعيين جميع الخصائص إلى قيمها الافتراضية. |

### قيمة الإرجاع

الـ [IAutoShape](../../iautoshape/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)