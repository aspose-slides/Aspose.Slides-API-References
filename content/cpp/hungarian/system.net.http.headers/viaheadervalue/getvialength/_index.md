---
title: GetViaLength()
second_title: Aspose.Slides C++ API Referenciája
description: Átalakítja a megadott indexről átadott karakterláncot a ViaHeaderValue osztály egy példányává.
type: docs
weight: 131
url: /hu/system.net.http.headers/viaheadervalue/getvialength/
---
## ViaHeaderValue::GetViaLength(String, int32_t, System::SharedPtr\<Object\>\&) metódus

Átalakítja a megadott indexről átadott karakterláncot a(z) [ViaHeaderValue](../) osztály egy példányává.

```cpp
static int32_t System::Net::Http::Headers::ViaHeaderValue::GetViaLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | [String](../../../system/string/) | A feldolgozandó karakterlánc. |
| startIndex | **int32_t** | A feldolgozáshoz használt kezdőpozíció. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Az a példány, amelyhez a feldolgozott objektum lesz hozzárendelve. |

### Visszatérési érték

Visszaadja a feldolgozott részkarakterlánc hosszát, egyébként 0.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [Object](../../../system/object/)
* Osztály [ViaHeaderValue](../)
* Névtér [System::Net::Http::Headers](../../)
* Könyvtár [Aspose.Slides](../../../)