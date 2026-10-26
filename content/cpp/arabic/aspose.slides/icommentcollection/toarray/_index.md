---
title: ToArray()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ ويعيد مصفوفة تحتوي على جميع التعليقات.
type: docs
weight: 66
url: /ar/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() طريقة

ينشئ ويعيد مصفوفة تحتوي على جميع التعليقات.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```

### قيمة الإرجاع

مصفوفة من [IComment](../../icomment/).

## ICommentCollection::ToArray(int32_t, int32_t) طريقة

ينشئ ويعيد مصفوفة تحتوي على جميع التعليقات من النطاق المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | **int32_t** | فهرس أول تعليق لإرجاعه. |
| count | **int32_t** | عدد التعليقات لإرجاعها. |

### قيمة الإرجاع

مصفوفة من [IComment](../../icomment/).

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IComment](../../icomment/)
* فئة [ICommentCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)