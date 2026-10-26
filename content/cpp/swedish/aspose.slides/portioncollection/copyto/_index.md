---
title: CopyTo()
second_title: Aspose.Slides för C++ API-referens
description: "Kopierar elementen i ICollection till en System::Array, med början vid ett särskilt System::Array-index."
type: docs
weight: 118
url: /sv/aspose.slides/portioncollection/copyto/
---
## PortionCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IPortion\>\>, int32_t) method

Kopierar elementen från [ICollection](../../../system.collections.generic/icollection/) till en [System::Array](../../../system/array/), med början vid ett särskilt [System::Array](../../../system/array/) index.

```cpp
void Aspose::Slides::PortionCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IPortion>> array, int32_t arrayIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\>\> | Den endimensionella [System::Array](../../../system/array/) som är målet för elementen som kopieras från [ICollection](../../../system.collections.generic/icollection/). [System::Array](../../../system/array/) måste ha nollbaserad indexering. |
| arrayIndex | **int32_t** | Det nollbaserade indexet i *array* där kopieringen börjar. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPortion](../../iportion/)
* Klass [PortionCollection](../)
* namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)