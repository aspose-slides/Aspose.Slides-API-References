---
title: ToString()
second_title: Aspose.Slides dla C++ API Reference
description: Konwertuje GUID reprezentowany przez bieżący obiekt do jego reprezentacji jako ciąg znaków.
type: docs
weight: 79
url: /pl/system/guid/tostring/
---
## Guid::ToString() const metoda


Konwertuje GUID reprezentowany przez bieżący obiekt do jego reprezentacji jako ciąg znaków.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const metoda


Konwertuje GUID reprezentowany przez bieżący obiekt do jego reprezentacji jako ciąg znaków przy użyciu określonego formatu ciągu znaków.

```cpp
String System::Guid::ToString(const String &format) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Format do użycia |

### Wartość zwracana

Reprezentacja ciągu znaków wartości GUID reprezentowanej przez bieżący obiekt

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metoda


Konwertuje GUID reprezentowany przez bieżący obiekt do jego reprezentacji jako ciąg znaków przy użyciu określonego formatu ciągu znaków oraz kultury.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Format do użycia |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura do użycia |

### Wartość zwracana

Reprezentacja ciągu znaków wartości GUID reprezentowanej przez bieżący obiekt

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [Guid](../)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)