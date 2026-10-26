---
title: TryGetBuffer()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a nem aláírt bájtok tömbjét, amelyből ez a stream lett létrehozva.
type: docs
weight: 170
url: /hu/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) metódus


Visszaadja a nem aláírt bájtok tömbjét, amelyből ez a stream lett létrehozva.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | byte tömb - kimenő paraméter. Ha ez a metódus true értékkel tér vissza, a byte tömb szegmens, amelyből ez a stream lett létrehozva; ha ez a metódus false értékkel tér vissza, ez a paraméter az alapértelmezett értékre van állítva. |

### Visszatérési érték

True, ha a konverzió sikeres volt.

## Lásd még

* Osztály [ArraySegment](../../../system/arraysegment/)
* Osztály [MemoryStream](../)
* Névtere [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)