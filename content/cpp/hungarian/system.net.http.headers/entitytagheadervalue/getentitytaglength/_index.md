---
title: GetEntityTagLength()
second_title: Aspose.Slides C++ API hivatkozás
description: Átalakítja a megadott karakterláncot a megadott indexről a EntityTagHeaderValue osztály egy példányává.
type: docs
weight: 118
url: /hu/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) metódus

Átalakítja a megadott karakterláncot a megadott indexről a [EntityTagHeaderValue](../) osztály egy példányává.

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | [String](../../../system/string/) | Az értelmezendő karakterlánc. |
| startIndex | **int32_t** | Az értelmezés kezdőpozíciója. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | Az a példány, amelybe a feldolgozott objektum lesz hozzárendelve. |

### Visszatérési érték

A feldolgozott részkarakterlánc hossza, egyébként 0.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [EntityTagHeaderValue](../)
* Névtér [System::Net::Http::Headers](../../)
* Könyvtár [Aspose.Slides](../../../)