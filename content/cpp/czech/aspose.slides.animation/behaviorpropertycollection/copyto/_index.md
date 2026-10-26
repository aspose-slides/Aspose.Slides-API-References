---
title: CopyTo()
second_title: "Aspose.Slides pro C++ referenci API"
description: "Zkopíruje prvky ICollection do System::Array, počínaje konkrétním indexem System::Array."
type: docs
weight: 66
url: /cs/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) metoda

Zkopíruje prvky [ICollection](../../../system.collections.generic/icollection/) do [System::Array](../../../system/array/), počínaje konkrétním indexem [System::Array](../../../system/array/).

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | Jednorozměrné [System::Array](../../../system/array/), které je cílem prvků zkopírovaných z [ICollection](../../../system.collections.generic/icollection/). [System::Array](../../../system/array/) musí mít nulové indexování. |
| arrayIndex | **int32_t** | Index založený na nule v *array*, kde začíná kopírování. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IBehaviorProperty](../../ibehaviorproperty/)
* Třída [BehaviorPropertyCollection](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)