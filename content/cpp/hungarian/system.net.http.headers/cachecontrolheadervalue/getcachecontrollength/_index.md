---
title: GetCacheControlLength()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott indexnél kezdődő karakterláncot a CacheControlHeaderValue osztály egy példányává.
type: docs
weight: 456
url: /hu/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) metódus


Átalakítja a megadott indexnél kezdődő karakterláncot a [CacheControlHeaderValue](../) osztály egy példányává.

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | [String](../../../system/string/) | A feldolgozandó karakterlánc. |
| startIndex | **int32_t** | A feldolgozás kezdőpozíciója. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | Az érték, amelyet hozzá kell adni a feldolgozott objektumhoz. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | Egy példány, amelyhez a feldolgozott objektum lesz hozzárendelve. |

### Visszatérési érték

A feldolgozott részkarakterlánc hossza, egyébként 0.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [CacheControlHeaderValue](../)
* Névtér [System::Net::Http::Headers](../../)
* Könyvtár [Aspose.Slides](../../../)