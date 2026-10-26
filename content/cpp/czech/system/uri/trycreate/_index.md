---
title: TryCreate()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří objekt Uri, který představuje zadané URI; argument určuje typ URI.
type: docs
weight: 508
url: /cs/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) metoda

Vytvoří objekt [Uri](../) představující zadané URI; argument určuje typ URI.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Řetězcové URI, které má být reprezentováno vytvářeným objektem |
| uriKind | [UriKind](../../urikind/) | Určuje typ URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Výstupní argument, který při úspěšném vytvoření ukazuje na nově vytvořený objekt [Uri](../) při návratu metody |

### Návratová hodnota

True, pokud bylo vytvoření úspěšné, jinak - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) metoda

Vytvoří objekt [Uri](../) z určeného objektu [Uri](../) představujícího základní URI a řetězcové reprezentace relativního URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Základní URI |
| relativeUri | const [String](../../string/)\& | Relativní URI, které se přidá k základnímu URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Výstupní argument, který při úspěšném vytvoření ukazuje na nově vytvořený objekt [Uri](../) při návratu metody |

### Návratová hodnota

True, pokud bylo vytvoření úspěšné, jinak - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) metoda


Vytvoří objekt [Uri](../) z určených základního a relativního URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Základní URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Relativní URI, které se přidá k základnímu URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Výstupní argument, který při úspěšném vytvoření ukazuje na nově vytvořený objekt [Uri](../) při návratu metody |

### Návratová hodnota

True, pokud bylo vytvoření úspěšné, jinak - false

## Viz také

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)