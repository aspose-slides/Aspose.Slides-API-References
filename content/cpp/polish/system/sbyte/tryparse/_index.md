---
title: TryParse()
second_title: Aspose.Slides dla C++ – referencja API
description: Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 8-bitową liczbę całkowitą ze znakiem.
type: docs
weight: 14
url: /pl/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji. |
| result | **int8_t**\& | Referencja do zmiennej 8-bitowej liczby całkowitej ze znakiem, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

True jeśli konwersja zakończyła się sukcesem, w przeciwnym razie - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 8-bitową liczbę całkowitą ze znakiem, używając dostarczonych informacji o formatowaniu oraz stylu liczby.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby w ciągu znaków. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków. |
| result | **int8_t**\& | Referencja do zmiennej 8-bitowej liczby całkowitej ze znakiem, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

True jeśli konwersja zakończyła się sukcesem, w przeciwnym razie - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) metoda




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) metoda




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) metoda




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## Zobacz także

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)