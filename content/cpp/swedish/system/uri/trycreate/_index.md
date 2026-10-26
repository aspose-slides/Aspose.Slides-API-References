---
title: TryCreate()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett Uri-objekt som representerar den angivna URI:n; ett argument anger URI-typen.
type: docs
weight: 508
url: /sv/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method

Skapar ett [Uri](../)-objekt som representerar den angivna URI:n; ett argument anger URI-typen.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | URI-strängen som ska representeras av objektet som konstrueras |
| uriKind | [UriKind](../../urikind/) | Anger URI-typen |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Utdataargumentet som, om konstruktionen lyckas, pekar på det nykonstruerade [Uri](../)-objektet vid metodens retur |

### Returvärde

Sant om konstruktionen lyckades, annars - falskt

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method

Skapar ett [Uri](../)-objekt från det angivna [Uri](../)-objektet som representerar bas-URI och den relativa URI-ns strängrepresentation.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Bas-URI:n |
| relativeUri | const [String](../../string/)\& | Den relativa URI:n som läggs till bas-URI:n |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Utdataargumentet som, om konstruktionen lyckas, pekar på det nykonstruerade [Uri](../)-objektet vid metodens retur |

### Returvärde

Sant om konstruktionen lyckades, annars - falskt

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method

Skapar ett [Uri](../)-objekt från de angivna bas- och relativa URI-erna.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Bas-URI:n |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Den relativa URI:n som läggs till bas-URI:n |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Utdataargumentet som, om konstruktionen lyckas, pekar på det nykonstruerade [Uri](../)-objektet vid metodens retur |

### Returvärde

Sant om konstruktionen lyckades, annars - falskt

## Se också

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)