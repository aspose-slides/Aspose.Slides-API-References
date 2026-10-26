---
title: CopyTo()
second_title: Aspose.Slides for C++ API Referansı
description: "ICollection öğelerinin bir System::Array'ye kopyalanması, belirli bir System::Array dizininde başlayarak."
type: docs
weight: 66
url: /tr/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) method

[ICollection](../../../system.collections.generic/icollection/) öğelerini bir [System::Array](../../../system/array/)'ye kopyalar, belirli bir [System::Array](../../../system/array/) indeksinde başlayarak.

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | [ICollection](../../../system.collections.generic/icollection/)'dan kopyalanan öğelerin hedefi olan tek boyutlu [System::Array](../../../system/array/). [System::Array](../../../system/array/) sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | **int32_t** | Kopyalamanın başladığı *array* içindeki sıfır tabanlı indeks. |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBehaviorProperty](../../ibehaviorproperty/)
* Class [BehaviorPropertyCollection](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)