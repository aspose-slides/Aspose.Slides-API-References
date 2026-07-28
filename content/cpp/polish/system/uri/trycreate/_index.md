---
title: TryCreate()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Tworzy obiekt Uri, który reprezentuje określony URI; argument określa rodzaj URI.
type: docs
weight: 508
url: /pl/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method

Tworzy obiekt [Uri](../) reprezentujący określony URI; argument określa rodzaj URI.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Ciąg znaków URI, który ma być reprezentowany przez tworzony obiekt |
| uriKind | [UriKind](../../urikind/) | Określa rodzaj URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Argument wyjściowy, który w przypadku pomyślnej konstrukcji wskazuje na nowo utworzony obiekt [Uri](../) przy zwrocie z metody |

### Wartość zwracana

True jeśli konstrukcja się powiodła, w przeciwnym razie - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method

Tworzy obiekt [Uri](../) z określonego obiektu [Uri](../) reprezentującego bazowy URI oraz z łańcuchowej reprezentacji względnego URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Bazowy URI |
| relativeUri | const [String](../../string/)\& | Względny URI, który jest dodawany do bazowego URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Argument wyjściowy, który w przypadku pomyślnej konstrukcji wskazuje na nowo utworzony obiekt [Uri](../) przy zwrocie z metody |

### Wartość zwracana

True jeśli konstrukcja się powiodła, w przeciwnym razie - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method

Tworzy obiekt [Uri](../) z określonych bazowych i względnych URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Bazowy URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Względny URI, który jest dodawany do bazowego URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Argument wyjściowy, który w przypadku pomyślnej konstrukcji wskazuje na nowo utworzony obiekt [Uri](../) przy zwrocie z metody |

### Wartość zwracana

True jeśli konstrukcja się powiodła, w przeciwnym razie - false

## Zobacz także

* Wyliczenie [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [Uri](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)