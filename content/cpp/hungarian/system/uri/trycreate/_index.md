---
title: TryCreate()
second_title: Aspose.Slides C++ API Referencia
description: Létrehoz egy Uri objektumot, amely a megadott URI-t képviseli; egy argumentum határozza meg az URI típusát.
type: docs
weight: 508
url: /hu/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) metódus


Létrehoz egy [Uri](../) objektumot, amely a megadott URI-t képviseli; egy argumentum határozza meg az URI típusát.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | A string URI, amelyet a létrehozott objektum képvisel |
| uriKind | [UriKind](../../urikind/) | Megadja az URI típusát |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | A kimeneti argumentum, amely ha a konstrukció sikeres, a metódus visszatérésekor az újonnan létrehozott [Uri](../) objektumra mutat |

### Visszatérési érték

True if the construction succeeded, otherwise - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) metódus


Létrehoz egy [Uri](../) objektumot a megadott [Uri](../) objektumból, amely az alap URI-t képviseli, valamint a relatív URI string ábrázolásából.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Az alap URI |
| relativeUri | const [String](../../string/)\& | A relatív URI, amelyet az alap URI-hez adnak hozzá |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | A kimeneti argumentum, amely ha a konstrukció sikeres, a metódus visszatérésekor az újonnan létrehozott [Uri](../) objektumra mutat |

### Visszatérési érték

True if the construction succeeded, otherwise - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) metódus


Létrehoz egy [Uri](../) objektumot a megadott alap és relatív URI-kból.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Az alap URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | A relatív URI, amelyet az alap URI-hez adnak hozzá |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | A kimeneti argumentum, amely ha a konstrukció sikeres, a metódus visszatérésekor az újonnan létrehozott [Uri](../) objektumra mutat |

### Visszatérési érték

True if the construction succeeded, otherwise - false

## Lásd még

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)