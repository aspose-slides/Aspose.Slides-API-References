---
title: ToArray()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ ويعيد مصفوفة تحتوي على جميع التعليقات.
type: docs
weight: 105
url: /ar/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() طريقة

ينشئ ويعيد مصفوفة تحتوي على جميع التعليقات.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```

### قيمة الإرجاع

مصفوفة من [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) طريقة

ينشئ ويعيد مصفوفة تحتوي على جميع التعليقات من النطاق المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | **int32_t** | فهرس أول تعليقة لإرجاعها. |
| count | **int32_t** | عدد التعليقات لإرجاعها. |

### قيمة الإرجاع

مصفوفة من [Comment](../../comment/).

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IComment](../../icomment/)
* فئة [CommentCollection](../)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)