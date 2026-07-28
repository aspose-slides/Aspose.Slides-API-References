---
title: Parse()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konwertuje podany ciąg znaków zawierający reprezentację liczby jako tekst na równoważną 8-bitową liczbę całkowitą ze znakiem.
type: docs
weight: 1
url: /pl/system/sbyte/parse/
---
## SByte::Parse(const String\&) method

Konwertuje podany ciąg znaków zawierający reprezentację liczby jako tekst na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static int8_t System::SByte::Parse(const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |

### Wartość zwracana

8-bitowa liczba całkowita ze znakiem równa liczbie reprezentowanej przez podany ciąg znaków.

## SByte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method

Konwertuje podany ciąg znaków zawierający reprezentację liczby jako tekst na równoważną 8-bitową liczbę całkowitą ze znakiem, wykorzystując dostarczone informacje o formatowaniu.

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków. |

### Wartość zwracana

8-bitowa liczba całkowita ze znakiem równa liczbie reprezentowanej przez podany ciąg znaków.

## SByte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, std::nullptr_t) method




```cpp
static int8_t System::SByte::Parse(const String &value, std::nullptr_t)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

Konwertuje podany ciąg znaków zawierający reprezentację liczby jako tekst na równoważną 8-bitową liczbę całkowitą ze znakiem, wykorzystując dostarczone informacje o formatowaniu i styl liczby.

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby jako tekst. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków. |

### Wartość zwracana

8-bitowa liczba całkowita ze znakiem równa liczbie reprezentowanej przez podany ciąg znaków.

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Zobacz także

* Wyliczenie [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktura [SByte](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)