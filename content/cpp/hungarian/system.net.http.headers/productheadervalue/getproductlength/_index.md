---
title: GetProductLength()
second_title: Aspose.Slides C++ API Referencia
description: Átalakítja a megadott indexről átadott karakterláncot a ProductHeaderValue osztály egy példányává.
type: docs
weight: 105
url: /hu/system.net.http.headers/productheadervalue/getproductlength/
---
## ProductHeaderValue::GetProductLength(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) metódus

Átalakítja a megadott indexről átadott stringet a [ProductHeaderValue](../) osztály egy példányává.

```cpp
static int32_t System::Net::Http::Headers::ProductHeaderValue::GetProductLength(String input, int32_t startIndex, System::SharedPtr<ProductHeaderValue> &parsedValue)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | [String](../../../system/string/) | A feldolgozandó string. |
| startIndex | **int32_t** | A feldolgozás kezdőpozíciója. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | Egy példány, ahová a feldolgozott objektum kerül hozzárendelésre. |

### Visszatérési érték

Visszaadja a feldolgozott részsztring hosszát, egyébként 0.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [ProductHeaderValue](../)
* Névtér [System::Net::Http::Headers](../../)
* Könyvtár [Aspose.Slides](../../../)