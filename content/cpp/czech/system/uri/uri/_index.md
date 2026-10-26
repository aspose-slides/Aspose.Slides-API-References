---
title: Uri()
second_title: Aspose.Slides pro C++ - reference API
description: Vytvoří objekt Uri, který představuje zadané URI.
type: docs
weight: 287
url: /cs/system/uri/uri/
---
## Uri::Uri(const String\&) konstruktor

Vytvoří objekt [Uri](../), který představuje zadané URI.

```cpp
System::Uri::Uri(const String &uriString)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Řetězec URI, který má být reprezentován vytvářeným objektem |

## Uri::Uri(const String\&, bool) konstruktor

Vytvoří objekt [Uri](../), který představuje zadané URI; argument určuje, zda má být URI escapováno.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Řetězec URI, který má být reprezentován vytvářeným objektem |
| dontEscape | **bool** | Určuje, zda má být URI neescapováno |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) konstruktor

Vytvoří objekt [Uri](../) z uvedeného objektu [Uri](../), který představuje základní URI, a řetězcového vyjádření relativního URI; argument určuje, zda má být URI escapováno.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Základní URI |
| relativeUri | const [String](../../string/)\& | Relativní URI, který se přidá k základnímu URI |
| dontEscape | **bool** | Určuje, zda má být URI neescapováno |

## Uri::Uri(const String\&, UriKind) konstruktor

Vytvoří objekt [Uri](../), který představuje zadané URI; argument určuje typ URI.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Řetězec URI, který má být představován vytvářeným objektem |
| uriKind | [UriKind](../../urikind/) | Určuje typ URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) konstruktor

Vytvoří objekt [Uri](../) z uvedených základního a relativního URI.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Základní URI |
| relativeUri | const [String](../../string/)\& | Relativní URI, který se přidá k základnímu URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) konstruktor

Vytvoří objekt [Uri](../) z uvedených základního a relativního URI.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Základní URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Relativní URI, který se přidá k základnímu URI |

## Viz také

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* třída [String](../../string/)
* třída [Uri](../)
* jmenný prostor [System](../../)
* knihovna [Aspose.Slides](../../../)