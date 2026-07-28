---
title: Parse()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Konwertuje podany ciąg znaków zawierający reprezentację liczby w postaci tekstowej na równoważną 64-bitową liczbę całkowitą bez znaku.
type: docs
weight: 1
url: /pl/system/uint64/parse/
---
## UInt64::Parse(const String\&) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby w postaci tekstowej na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |

### Wartość zwracana

64-bitowa liczba całkowita bez znaku równa liczbie reprezentowanej przez podany ciąg znaków.

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 64-bitową liczbę całkowitą bez znaku, używając dostarczonych informacji o formatowaniu.

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków. |

### Wartość zwracana

64-bitowa liczba całkowita bez znaku równa liczbie reprezentowanej przez podany ciąg znaków.

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) metoda

```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 64-bitową liczbę całkowitą bez znaku, używając dostarczonych informacji o formatowaniu oraz stylu liczby.

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby w ciągu znaków. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków. |

### Wartość zwracana

64-bitowa liczba całkowita bez znaku równa liczbie reprezentowanej przez podany ciąg znaków.

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Zobacz także

* Wyliczenie [NumberStyles](../../../system.globalization/numberstyles/)
* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktura [UInt64](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)