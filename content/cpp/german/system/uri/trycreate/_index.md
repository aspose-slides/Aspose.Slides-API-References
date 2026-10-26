---
title: TryCreate()
second_title: Aspose.Slides für C++ API Referenz
description: Konstruiert ein Uri-Objekt, das die angegebene URI darstellt; ein Argument gibt den URI-Typ an.
type: docs
weight: 508
url: /de/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method


Konstruiert ein [Uri](../) Objekt, das die angegebene URI darstellt; ein Argument gibt den URI-Typ an.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Die Zeichenketten-URI, die durch das zu konstruierende Objekt dargestellt werden soll |
| uriKind | [UriKind](../../urikind/) | Gibt den URI-Typ an |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Das Ausgabe-Argument, das bei erfolgreicher Konstruktion bei Rückkehr der Methode auf das neu konstruierte [Uri](../) Objekt zeigt |

### Rückgabewert

True, wenn die Konstruktion erfolgreich war, sonst - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method


Konstruiert ein [Uri](../) Objekt aus dem angegebenen [Uri](../) Objekt, das die Basis-URI darstellt, und der Zeichenkettenrepräsentation der relativen URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Die Basis-URI |
| relativeUri | const [String](../../string/)\& | Die relative URI, die zur Basis-URI hinzugefügt wird |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Das Ausgabe-Argument, das bei erfolgreicher Konstruktion bei Rückkehr der Methode auf das neu konstruierte [Uri](../) Objekt zeigt |

### Rückgabewert

True, wenn die Konstruktion erfolgreich war, sonst - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method


Konstruiert ein [Uri](../) Objekt aus den angegebenen Basis- und relativen URIs.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Die Basis-URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Die relative URI, die zur Basis-URI hinzugefügt wird |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Das Ausgabe-Argument, das bei erfolgreicher Konstruktion bei Rückkehr der Methode auf das neu konstruierte [Uri](../) Objekt zeigt |

### Rückgabewert

True, wenn die Konstruktion erfolgreich war, sonst - false

## Siehe auch

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)