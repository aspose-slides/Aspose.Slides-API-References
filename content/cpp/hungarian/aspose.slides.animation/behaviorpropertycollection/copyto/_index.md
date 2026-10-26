---
title: CopyTo()
second_title: Aspose.Slides for C++ API referencia
description: "Átmásolja az ICollection elemeit egy System::Array-be, egy adott System::Array indexnél kezdve."
type: docs
weight: 66
url: /hu/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) metódus

Másolja a(z) [ICollection](../../../system.collections.generic/icollection/) elemeit egy [System::Array](../../../system/array/)-ba, egy adott [System::Array](../../../system/array/) indexnél kezdve.

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | Az egy dimenziós [System::Array](../../../system/array/), amely a [ICollection](../../../system.collections.generic/icollection/)-ból másolt elemek célja. A [System::Array](../../../system/array/)-nek nulláral kezdődő indexelést kell használni. |
| arrayIndex | **int32_t** | A nulláral kezdődő index az *array*-ben, ahol a másolás elkezdődik. |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IBehaviorProperty](../../ibehaviorproperty/)
* Osztály [BehaviorPropertyCollection](../)
* Névtér [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)