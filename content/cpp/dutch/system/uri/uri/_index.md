---
title: Uri()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een Uri-object dat de opgegeven URI vertegenwoordigt.
type: docs
weight: 287
url: /nl/system/uri/uri/
---
## Uri::Uri(const String\&) constructor


Construeert een [Uri](../) object dat de opgegeven URI vertegenwoordigt.

```cpp
System::Uri::Uri(const String &uriString)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | De string-URI die moet worden weergegeven door het te construeren object |
|  |  |  |

## Uri::Uri(const String\&, bool) constructor


Construeert een [Uri](../) object dat de opgegeven URI vertegenwoordigt; een argument geeft aan of de URI moet worden ontsnapt.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | De string-URI die moet worden weergegeven door het te construeren object |
| dontEscape | **bool** | Geeft aan of de URI niet moet worden ontsnapt |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) constructor


Construeert een [Uri](../) object uit het opgegeven [Uri](../) object dat de basis-URI vertegenwoordigt en de tekenreeksweergave van de relatieve URI; een argument geeft aan of de URI moet worden ontsnapt.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | De basis-URI |
| relativeUri | const [String](../../string/)\& | De relatieve URI die aan de basis-URI wordt toegevoegd |
| dontEscape | **bool** | Geeft aan of de URI niet moet worden ontsnapt |

## Uri::Uri(const String\&, UriKind) constructor


Construeert een [Uri](../) object dat de opgegeven URI vertegenwoordigt; een argument geeft het URI-type aan.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | De string-URI die moet worden weergegeven door het te construeren object |
| uriKind | [UriKind](../../urikind/) | Geeft het URI-type aan |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) constructor


Construeert een [Uri](../) object uit de opgegeven basis- en relatieve URI’s.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | De basis-URI |
| relativeUri | const [String](../../string/)\& | De relatieve URI die aan de basis-URI wordt toegevoegd |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) constructor


Construeert een [Uri](../) object uit de opgegeven basis- en relatieve URI’s.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | De basis-URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | De relatieve URI die aan de basis-URI wordt toegevoegd |

## Zie ook

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Uri](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)