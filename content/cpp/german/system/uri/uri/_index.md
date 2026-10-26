---
title: Uri()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Uri-Objekt, das die angegebene URI darstellt.
type: docs
weight: 287
url: /de/system/uri/uri/
---
## Uri::Uri(const String\&) Konstruktor

Erstellt ein [Uri](../) Objekt, das die angegebene URI darstellt.

```cpp
System::Uri::Uri(const String &uriString)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Der Zeichenketten-URI, der vom zu erstellenden Objekt dargestellt wird |

## Uri::Uri(const String\&, bool) Konstruktor

Erstellt ein [Uri](../) Objekt, das die angegebene URI darstellt; ein Argument gibt an, ob die URI escaped werden soll.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Der Zeichenketten-URI, der vom zu erstellenden Objekt dargestellt wird |
| dontEscape | **bool** | Gibt an, ob die URI nicht escaped werden soll |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) Konstruktor

Erstellt ein [Uri](../) Objekt aus dem angegebenen [Uri](../) Objekt, das die Basis-URI darstellt, und der Zeichenketten-Darstellung der relativen URI; ein Argument gibt an, ob die URI escaped werden soll.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Die Basis-URI |
| relativeUri | const [String](../../string/)\& | Die relative URI, die zur Basis-URI hinzugefügt wird |
| dontEscape | **bool** | Gibt an, ob die URI nicht escaped werden soll |

## Uri::Uri(const String\&, UriKind) Konstruktor

Erstellt ein [Uri](../) Objekt, das die angegebene URI darstellt; ein Argument gibt den URI-Typ an.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Der Zeichenketten-URI, der vom zu erstellenden Objekt dargestellt wird |
| uriKind | [UriKind](../../urikind/) | Gibt den URI-Typ an |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) Konstruktor

Erstellt ein [Uri](../) Objekt aus den angegebenen Basis- und relativen URIs.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Die Basis-URI |
| relativeUri | const [String](../../string/)\& | Die relative URI, die zur Basis-URI hinzugefügt wird |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) Konstruktor

Erstellt ein [Uri](../) Objekt aus den angegebenen Basis- und relativen URIs.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Die Basis-URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Die relative URI, die zur Basis-URI hinzugefügt wird |

## Siehe auch

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Uri](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)