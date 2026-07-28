---
title: TryParse()
second_title: Aspose.Slides dla C++ – referencja API
description: Konwertuje podany ciąg zawierający reprezentację liczby na równoważną 16-bitową liczbę całkowitą bez znaku.
type: docs
weight: 14
url: /pl/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) metoda


Konwertuje podany ciąg zawierający reprezentację liczby na równoważną 16-bitową liczbę całkowitą bez znaku.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji. |
| result | **uint16_t**\& | Referencja do zmiennej typu uint16_t, do której zostanie wpisany wynik konwersji. |

### Wartość zwracana

true, jeśli konwersja się powiodła, w przeciwnym razie – false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) metoda


Konwertuje podany ciąg zawierający reprezentację liczby na równoważną 16-bitową liczbę całkowitą bez znaku, używając podanych informacji o formatowaniu i stylu liczby.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles, określająca dozwolony styl reprezentacji liczby w ciągu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu. |
| result | **uint16_t**\& | Referencja do zmiennej typu uint16_t, do której zostanie wpisany wynik konwersji. |

### Wartość zwracana

true, jeśli konwersja się powiodła, w przeciwnym razie – false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) metoda




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) metoda




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) metoda




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## Zobacz także

* Wyliczenie [NumberStyles](../../../system.globalization/numberstyles/)
* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktura [UInt16](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)