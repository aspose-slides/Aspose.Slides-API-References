---
title: Uri()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehoz egy Uri objektumot, amely a megadott URI-t reprezentálja.
type: docs
weight: 287
url: /hu/system/uri/uri/
---
## Uri::Uri(const String\&) konstruktor

Létrehoz egy [Uri](../) objektumot, amely a megadott URI-t reprezentálja.

```cpp
System::Uri::Uri(const String &uriString)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | A karakterlánc URI, amelyet a létrehozott objektum képvisel |

## Uri::Uri(const String\&, bool) konstruktor

Létrehoz egy [Uri](../) objektumot, amely a megadott URI-t reprezentálja; egy argumentum megadja, hogy az URI ne legyen escape-elve.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | A karakterlánc URI, amelyet a létrehozott objektum képvisel |
| dontEscape | **bool** | Megadja, hogy az URI ne legyen escape-elve |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) konstruktor

Létrehoz egy [Uri](../) objektumot a megadott [Uri](../) objektumból, amely az alap URI-t reprezentálja, és a relatív URI karakterlánc ábrázolásából; egy argumentum megadja, hogy az URI escape-elve legyen-e.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Az alap URI |
| relativeUri | const [String](../../string/)\& | A relatív URI, amelyet az alap URI-hoz adunk |
| dontEscape | **bool** | Megadja, hogy az URI ne legyen escape-elve |

## Uri::Uri(const String\&, UriKind) konstruktor

Létrehoz egy [Uri](../) objektumot, amely a megadott URI-t reprezentálja; egy argumentum megadja az URI típusát.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | A karakterlánc URI, amelyet a létrehozott objektum képvisel |
| uriKind | [UriKind](../../urikind/) | Megadja az URI típusát |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) konstruktor

Létrehoz egy [Uri](../) objektumot a megadott alap és relatív URI-kból.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Az alap URI |
| relativeUri | const [String](../../string/)\& | A relatív URI, amelyet az alap URI-hoz adunk |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) konstruktor

Létrehoz egy [Uri](../) objektumot a megadott alap és relatív URI-kból.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Az alap URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | A relatív URI, amelyet az alap URI-hoz adunk |

## Lásd még

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [Uri](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)