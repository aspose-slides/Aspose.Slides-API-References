---
title: GetHashCode()
second_title: Aspose.Slides for C++ API referencia
description: A C# Object.GetHashCode() metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését.
type: docs
weight: 53
url: /hu/system.net.http.headers/namevalueheadervalue/gethashcode/
---
## NameValueHeaderValue::GetHashCode() const metódus


A C# [Object.GetHashCode()](../../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését.

```cpp
int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode() const override
```


### Visszatérési érték

Hashkód érték, amelyet a megfelelő osztály számít ki.

## NameValueHeaderValue::GetHashCode(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) metódus


Visszaad egy hashkódot az összes gyűjteményelemhez.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | A NameValueHeaderValue osztálypéldányok gyűjteménye. |

### Visszatérési érték

Az összes gyűjteményelem hashkódja.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NameValueHeaderValue](../)
* Class [ObjectCollection](../../objectcollection/)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)