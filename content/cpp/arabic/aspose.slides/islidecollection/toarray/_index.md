---
title: ToArray()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ ويُعيد مصفوفة تحتوي على جميع الشرائح.
type: docs
weight: 92
url: /ar/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() طريقة

ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```

### قيمة الإرجاع

مصفوفة من [ISlide](../../islide/)

## ISlideCollection::ToArray(int32_t, int32_t) طريقة

ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح من النطاق المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### معاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| startIndex | **int32_t** | An index of a first slide to add. |
| count | **int32_t** | A number of slides to add. |

### قيمة الإرجاع

مصفوفة من [ISlide](../../islide/)

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)