---
title: ToArray()
second_title: مرجع API Aspose.Slides للغة C++
description: إنشاء وإرجاع مصفوفة تحتوي على جميع الأشكال.
type: docs
weight: 326
url: /ar/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() طريقة


إنشاء وإرجاع مصفوفة تحتوي على جميع الأشكال.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```


### قيمة الإرجاع

مصفوفة من كائنات [IShape](../../ishape/).

## ShapeCollection::ToArray(int32_t, int32_t) طريقة


إنشاء وإرجاع مصفوفة تحتوي على جميع الأشكال في النطاق المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```


### معاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | **int32_t** | المؤشر إلى أول شكل سيتم إرجاعه. |
| count | **int32_t** | عدد الأشكال التي سيتم إرجاعها. |

### قيمة الإرجاع

مصفوفة من كائنات [IShape](../../ishape/).

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IShape](../../ishape/)
* فئة [ShapeCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)