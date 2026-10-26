---
title: TryCreate()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een Uri-object dat de opgegeven URI voorstelt; een argument specificeert het type URI.
type: docs
weight: 508
url: /nl/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) methode


Construeert een [Uri](../) object dat de opgegeven URI voorstelt; een argument specificeert het type URI.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | De tekenreeks-URI die door het te construeren object wordt weergegeven |
| uriKind | [UriKind](../../urikind/) | Specificeert het type URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Het uitvoerargument dat, indien de constructie slaagt, bij terugkeer van de methode naar het nieuw geconstrueerde [Uri](../) object wijst |

### Retourwaarde

True als de constructie is geslaagd, anders - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) methode


Construeert een [Uri](../) object van het opgegeven [Uri](../) object dat de basis-URI voorstelt en de tekenreeksrepresentatie van de relatieve URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | De basis-URI |
| relativeUri | const [String](../../string/)\& | De relatieve URI die aan de basis-URI wordt toegevoegd |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Het uitvoerargument dat, indien de constructie slaagt, bij terugkeer van de methode naar het nieuw geconstrueerde [Uri](../) object wijst |

### Retourwaarde

True als de constructie is geslaagd, anders - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) methode


Construeert een [Uri](../) object van de opgegeven basis- en relatieve URI's.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | De basis-URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | De relatieve URI die aan de basis-URI wordt toegevoegd |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Het uitvoerargument dat, indien de constructie slaagt, bij terugkeer van de methode naar het nieuw geconstrueerde [Uri](../) object wijst |

### Retourwaarde

True als de constructie is geslaagd, anders - false

## Zie ook

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Uri](../)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)