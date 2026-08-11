---
title: CopyTo()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يقوم بنسخ عناصر ICollection إلى System::Array، بدءًا من فهرس System::Array معين."
type: docs
weight: 66
url: /ar/aspose.slides.animation/behaviorcollection/copyto/
---
## BehaviorCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehavior\>\>, int32_t) طريقة

يقوم بنسخ عناصر [ICollection](../../../system.collections.generic/icollection/) إلى [System::Array](../../../system/array/)، بدءًا من فهرس [System::Array](../../../system/array/) معين.

```cpp
void Aspose::Slides::Animation::BehaviorCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehavior>> array, int32_t arrayIndex)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehavior](../../ibehavior/)\>\> | المصفوفة أحادية البعد [System::Array](../../../system/array/) التي هي وجهة العناصر المنسوخة من [ICollection](../../../system.collections.generic/icollection/). يجب أن يكون [System::Array](../../../system/array/) بفهرسة صفرية. |
| arrayIndex | **int32_t** | الفهرس الذي يبدأ من الصفر في *array* الذي يبدأ عنده النسخ. |

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IBehavior](../../ibehavior/)
* فئة [BehaviorCollection](../)
* نطاق [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)