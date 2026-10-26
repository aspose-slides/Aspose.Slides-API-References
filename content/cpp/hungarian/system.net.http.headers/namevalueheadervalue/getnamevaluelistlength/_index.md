---
title: GetNameValueListLength()
second_title: Aspose.Slides C++ API-referencia
description: Átalakít egy megadott karakterláncot a megadott indexről a NameValueHeaderValue osztálypéldányainak gyűjteményébe, és visszaadja a feldolgozott részkarakterlánc hosszát.
type: docs
weight: 131
url: /hu/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) metódus

Átalakít egy megadott karakterláncot a megadott indextől a NameValueHeaderValue-osztály példányainak gyűjteményébe, és visszaadja a feldolgozott részkarakterlánc hosszát.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | [String](../../../system/string/) | Elemzendő karakterlánc. |
| startIndex | **int32_t** | Az elemzés kezdőpozíciója. |
| delimiter | char16_t | Az elemek elválasztására a megadott karakterláncban használt karakterlánc. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | A kimeneti paraméter, amelybe a feldolgozott gyűjteményt rendeljük. |

### Visszatérési érték

A feldolgozott részkarakterlánc hossza.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [ObjectCollection](../../objectcollection/)
* Osztály [NameValueHeaderValue](../)
* Névtér [System::Net::Http::Headers](../../)
* Könyvtár [Aspose.Slides](../../../)