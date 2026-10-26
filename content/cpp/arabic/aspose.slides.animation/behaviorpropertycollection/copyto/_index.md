---
title: CopyTo()
second_title: "Aspose.Slides لـ C++ مرجع API"
description: "ينسخ عناصر ICollection إلى System::Array، بدءًا من فهرس System::Array محدد."
type: docs
weight: 66
url: /ar/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) method

Copies the elements of the [ICollection](../../../system.collections.generic/icollection/) to an [System::Array](../../../system/array/), starting at a particular [System::Array](../../../system/array/) index.

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | مجموعة [System::Array](../../../system/array/) ذات بعد واحد التي هي الوجهة للعناصر المنقولة من [ICollection](../../../system.collections.generic/icollection/). يجب أن يكون [System::Array](../../../system/array/) ذات فهرسة بدءًا من الصفر. |
| arrayIndex | **int32_t** | الفهرس الذي يبدأ من الصفر في *array* حيث يبدأ النسخ. |

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IBehaviorProperty](../../ibehaviorproperty/)
* فئة [BehaviorPropertyCollection](../)
* نطاق [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)