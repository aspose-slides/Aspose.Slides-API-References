---
title: GetMediaTypeLength()
second_title: Aspose.Slides C++ API hivatkozás
description: Átalakít egy átadott karakterláncot a megadott indexről a MediaTypeHeaderValue osztály egy példányává.
type: docs
weight: 144
url: /hu/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) metódus

Átalakít egy átadott karakterláncot a megadott indexről a(z) [MediaTypeHeaderValue](../) osztály egy példányává.

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | [String](../../../system/string/) | Egy feldolgozandó karakterlánc. |
| startIndex | **int32_t** | Egy kezdőpozíció a feldolgozáshoz. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | Az a delegát, amelyet a(z) [MediaTypeHeaderValue](../) osztály példányainak létrehozásához használnak. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | Egy példány, amelybe a feldolgozott objektum kerül. |

### Visszatérési érték

Visszaadja a feldolgozott részkarakterlánc hosszát, egyébként 0.

## Lásd még

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [MediaTypeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)