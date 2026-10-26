---
title: InsertAutoShape()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ شكلاً تلقائيًا جديدًا ويدخله في مجموعة الأشكال في الفهرس المحدد، مطبقًا تنسيق القالب الافتراضي.
type: docs
weight: 378
url: /ar/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) طريقة

ينشئ شكلًا تلقائيًا جديدًا ويدخله في مجموعة الأشكال في الفهرس المحدد، مطبقًا تنسيق القالب الافتراضي.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | الفهرس المعتمد على الصفر الذي سيتم عنده إدراج الشكل التلقائي الجديد. |
| shapeType | [ShapeType](../../shapetype/) | الـ[ShapeType](../../shapetype/) من الشكل التلقائي المراد إدراجه. |
| x | **float** | إحداثي x لإطار الشكل، بالنقاط. |
| y | **float** | إحداثي y لإطار الشكل، بالنقاط. |
| width | **float** | عرض إطار الشكل، بالنقاط. |
| height | **float** | ارتفاع إطار الشكل، بالنقاط. |

### قيمة الإرجاع

الـ[IAutoShape](../../iautoshape/) الذي تم إنشاؤه حديثًا.

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) طريقة

ينشئ شكلًا تلقائيًا جديدًا ويدخله في مجموعة الأشكال في الفهرس المحدد، مع إمكانية تهيئته بنمط القالب الافتراضي.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | الفهرس المعتمد على الصفر الذي سيتم عنده إدراج الشكل التلقائي. |
| shapeType | [ShapeType](../../shapetype/) | الـ[ShapeType](../../shapetype/) من الشكل التلقائي المراد إدراجه. |
| x | **float** | إحداثي x لإطار الشكل، بالنقاط. |
| y | **float** | إحداثي y لإطار الشكل، بالنقاط. |
| width | **float** | عرض إطار الشكل، بالنقاط. |
| height | **float** | ارتفاع إطار الشكل، بالنقاط. |
| createFromTemplate | **bool** | True لتطبيق نمط القالب الافتراضي (بما في ذلك اسم غير فارغ، نمط بسيط، ونص مركّز)؛ false لإنشاء الشكل مع تعيين جميع الخصائص إلى القيم الافتراضية. |

### قيمة الإرجاع

الـ[IAutoShape](../../iautoshape/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)