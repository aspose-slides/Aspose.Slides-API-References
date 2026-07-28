---
title: GetNameValueLength()
second_title: Aspose.Slides C++ API hivatkozás
description: Átalakítja a megadott karakterláncot a megadott indexről a NameValueHeaderValue osztály egy példányává.
type: docs
weight: 118
url: /hu/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) metódus


Átalakítja a megadott karakterláncot a megadott indexről a [NameValueHeaderValue](../) osztály egy példányává.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | [String](../../../system/string/) | A feldolgozandó karakterlánc. |
| startIndex | **int32_t** | A feldolgozás kezdőpozíciója. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Egy példány, amelyhez a feldolgozott objektum lesz hozzárendelve. |

### Return Value

Visszaadja a feldolgozott részkarakterlánc hosszát, egyébként 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) metódus


Átalakítja a megadott karakterláncot a megadott indexről a [NameValueHeaderValue](../) osztály egy példányává.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | [String](../../../system/string/) | A feldolgozandó karakterlánc. |
| startIndex | **int32_t** | A feldolgozás kezdőpozíciója. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | Egy függvény, amely az új [NameValueHeaderValue](../) osztály példányok létrehozására szolgál. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Egy példány, amelyhez a feldolgozott objektum lesz hozzárendelve. |

### Return Value

Visszaadja a feldolgozott részkarakterlánc hosszát, egyébként 0.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Osztály [String](../../../system/string/)
* Osztály [NameValueHeaderValue](../)
* Névtér [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)