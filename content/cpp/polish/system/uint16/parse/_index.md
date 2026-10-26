---
title: Parse()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 16-bitową liczbę całkowitą bez znaku.
type: docs
weight: 1
url: /pl/system/uint16/parse/
---
## UInt16::Parse(const String\&) metoda


Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 16-bitową liczbę całkowitą bez znaku.

```cpp
static uint16_t System::UInt16::Parse(const String &value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |

### Wartość zwracana

16-bitowa liczba całkowita bez znaku równa liczbie przedstawionej w podanym ciągu znaków.

## UInt16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 16-bitową liczbę całkowitą bez znaku, wykorzystując podane informacje o formatowaniu.

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu znaków. |

### Wartość zwracana

16-bitowa liczba całkowita bez znaku równa liczbie przedstawionej w podanym ciągu znaków.

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, std::nullptr_t) metoda




```cpp
static uint16_t System::UInt16::Parse(const String &value, std::nullptr_t)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 16-bitową liczbę całkowitą bez znaku, wykorzystując podane informacje o formatowaniu oraz styl liczby.

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dopuszczalny styl reprezentacji liczby jako ciągu znaków. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu znaków. |

### Wartość zwracana

16-bitowa liczba całkowita bez znaku równa liczbie przedstawionej w podanym ciągu znaków.

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
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