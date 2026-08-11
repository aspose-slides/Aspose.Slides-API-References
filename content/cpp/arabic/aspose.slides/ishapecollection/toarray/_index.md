---
title: ToArray()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال.
type: docs
weight: 287
url: /ar/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() طريقة

ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```

### قيمة الإرجاع

مصفوفة من كائنات [IShape](../../ishape/).

## IShapeCollection::ToArray(int32_t, int32_t) طريقة

ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال في النطاق المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | **int32_t** | فهرس الشكل الأول الذي سيُعاد. |
| count | **int32_t** | عدد الأشكال التي سيُعاد. |

### قيمة الإرجاع

مصفوفة من كائنات [IShape](../../ishape/).

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)