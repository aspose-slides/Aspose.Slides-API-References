---
title: CopyTo()
second_title: Aspose.Slides för C++ API-referens
description: "Kopierar elementen i ICollection till en System::Array, med start på ett specifikt System::Array-index."
type: docs
weight: 66
url: /sv/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) metod


Kopierar elementen i [ICollection](../../../system.collections.generic/icollection/) till en [System::Array](../../../system/array/) med start på ett specifikt [System::Array](../../../system/array/)-index.

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | Den endimensionella [System::Array](../../../system/array/) som är destinationen för elementen som kopierats från [ICollection](../../../system.collections.generic/icollection/). [System::Array](../../../system/array/) måste ha nollbaserad indexering. |
| arrayIndex | **int32_t** | Det nollbaserade indexet i *array* där kopieringen börjar. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IBehaviorProperty](../../ibehaviorproperty/)
* Klass [BehaviorPropertyCollection](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)