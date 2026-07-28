---
title: TryParse()
second_title: Odwołanie API Aspose.Slides dla C++
description: Konwertuje podany ciąg zawierający reprezentację liczby w postaci tekstowej na równoważną 32-bitową liczbę całkowitą bez znaku.
type: docs
weight: 14
url: /pl/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) metoda

Konwertuje podany ciąg zawierający reprezentację liczby w postaci tekstowej na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji. |
| result | **uint32_t**\& | Odniesienie do zmiennej 32-bitowej liczby całkowitej bez znaku, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

True, jeśli konwersja się powiodła, w przeciwnym razie - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) metoda

Konwertuje podany ciąg zawierający reprezentację liczby w postaci tekstowej na równoważną 32-bitową liczbę całkowitą bez znaku przy użyciu podanych informacji formatowania i stylu liczby.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby w ciągu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu. |
| result | **uint32_t**\& | Odniesienie do zmiennej 32-bitowej liczby całkowitej bez znaku, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

True, jeśli konwersja się powiodła, w przeciwnym razie - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) metoda




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) metoda




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) metoda




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## Zobacz także

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktura [UInt32](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)