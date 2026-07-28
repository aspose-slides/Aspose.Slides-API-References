---
title: CopyTo()
second_title: Aspose.Slides C++ API Referencia
description: "Átmásolja az ICollection elemeit egy System::Array-be, egy adott System::Array indexnél kezdve."
type: docs
weight: 118
url: /hu/aspose.slides/portioncollection/copyto/
---
## PortionCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IPortion\>\>, int32_t) method

A [ICollection](../../../system.collections.generic/icollection/) elemeit egy [System::Array](../../../system/array/)-ba másolja, egy adott [System::Array](../../../system/array/) indexnél kezdve.

```cpp
void Aspose::Slides::PortionCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IPortion>> array, int32_t arrayIndex)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\>\> | Az egydimenziós [System::Array](../../../system/array/), amely a [ICollection](../../../system.collections.generic/icollection/)-ból másolt elemek célpontja. A [System::Array](../../../system/array/)-nek nullára indexeltnek kell lennie. |
| arrayIndex | **int32_t** | A nullára indexelt index az *array*-ban, ahol a másolás kezdődik. |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPortion](../../iportion/)
* Osztály [PortionCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)