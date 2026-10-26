---
title: Uri()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett Uri-objekt som representerar den angivna URI:n.
type: docs
weight: 287
url: /sv/system/uri/uri/
---
## Uri::Uri(const String\&) konstruktor


Skapar ett [Uri](../)-objekt som representerar den angivna URI:n.

```cpp
System::Uri::Uri(const String &uriString)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Sträng-URI:n som ska representeras av det objekt som konstrueras |

## Uri::Uri(const String\&, bool) konstruktor


Skapar ett [Uri](../)-objekt som representerar den angivna URI:n; ett argument anger om URI:n ska kodas.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Sträng-URI:n som ska representeras av det objekt som konstrueras |
| dontEscape | **bool** | Anger om URI:n inte ska kodas |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) konstruktor


Skapar ett [Uri](../)-objekt från det angivna [Uri](../)-objektet som representerar bas-URI:n och den strängrepresentation av relativ URI; ett argument anger om URI:n ska kodas.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Bas-URI:n |
| relativeUri | const [String](../../string/)\& | Den relativa URI:n som läggs till bas-URI:n |
| dontEscape | **bool** | Anger om URI:n inte ska kodas |

## Uri::Uri(const String\&, UriKind) konstruktor


Skapar ett [Uri](../)-objekt som representerar den angivna URI:n; ett argument anger URI-typen.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Sträng-URI:n som ska representeras av det objekt som konstrueras |
| uriKind | [UriKind](../../urikind/) | Anger URI-typen |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) konstruktor


Skapar ett [Uri](../)-objekt från de angivna bas- och relativa URI:erna.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Bas-URI:n |
| relativeUri | const [String](../../string/)\& | Den relativa URI:n som läggs till bas-URI:n |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) konstruktor


Skapar ett [Uri](../)-objekt från de angivna bas- och relativa URI:erna.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Bas-URI:n |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Den relativa URI:n som läggs till bas-URI:n |

## Se även

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [Uri](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)