---
title: GetRangeItemLength()
second_title: Aspose.Slides C++ API referencia
description: Átalakít egy megadott karakterláncot a megadott indexről a RangeItemHeaderValue osztály egy példányává.
type: docs
weight: 92
url: /hu/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) metódus

Átalakít egy megadott karakterláncot a megadott indexről a(z) [RangeItemHeaderValue](../) osztály egy példányává.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | [String](../../../system/string/) | A feldolgozandó karakterlánc. |
| startIndex | **int32_t** | A feldolgozás kezdőpozíciója. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | Egy példány, amelyhez a feldolgozott objektum lesz hozzárendelve. |

### Visszatérési érték

Visszaadja a feldolgozott részkarakterlánc hosszát, egyébként 0.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [RangeItemHeaderValue](../)
* Névtér [System::Net::Http::Headers](../../)
* Könyvtár [Aspose.Slides](../../../)