---
title: Uri()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Tworzy obiekt Uri, który reprezentuje określony URI.
type: docs
weight: 287
url: /pl/system/uri/uri/
---
## Uri::Uri(const String\&) konstruktor


Tworzy obiekt [Uri](../) reprezentujący określony URI.

```cpp
System::Uri::Uri(const String &uriString)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Ciąg znaków URI, który ma być reprezentowany przez tworzony obiekt |

## Uri::Uri(const String\&, bool) konstruktor


Tworzy obiekt [Uri](../) reprezentujący określony URI; argument określa, czy URI powinien być kodowany.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Ciąg znaków URI, który ma być reprezentowany przez tworzony obiekt |
| dontEscape | **bool** | Określa, czy URI nie powinien być kodowany |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) konstruktor


Tworzy obiekt [Uri](../) z określonego obiektu [Uri](../) reprezentującego bazowy URI oraz ciągowego przedstawienia względnego URI; argument określa, czy URI powinien być kodowany.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Bazowy URI |
| relativeUri | const [String](../../string/)\& | Względny URI, który jest dodawany do bazowego URI |
| dontEscape | **bool** | Określa, czy URI nie powinien być kodowany |

## Uri::Uri(const String\&, UriKind) konstruktor


Tworzy obiekt [Uri](../) reprezentujący określony URI; argument określa rodzaj URI.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Ciąg znaków URI, który ma być reprezentowany przez tworzony obiekt |
| uriKind | [UriKind](../../urikind/) | Określa rodzaj URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) konstruktor


Tworzy obiekt [Uri](../) z określonych bazowego i względnego URI.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Bazowy URI |
| relativeUri | const [String](../../string/)\& | Względny URI, który jest dodawany do bazowego URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) konstruktor


Tworzy obiekt [Uri](../) z określonych bazowego i względnego URI.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Bazowy URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Względny URI, który jest dodawany do bazowego URI |

## Zobacz także

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)