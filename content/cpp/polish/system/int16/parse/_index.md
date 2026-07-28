---
title: Parse()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Konwertuje podany ciąg znaków zawierający tekstową reprezentację liczby na równoważną 16-bitową liczbę całkowitą ze znakiem.
type: docs
weight: 1
url: /pl/system/int16/parse/
---
## Int16::Parse(const String\&) metoda

Konwertuje podany ciąg znaków zawierający tekstową reprezentację liczby na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static int16_t System::Int16::Parse(const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |

### Wartość zwracana

16-bitowa liczba całkowita ze znakiem równa liczbie przedstawionej w określonym ciągu znaków.

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podany ciąg znaków zawierający tekstową reprezentację liczby na równoważną 16-bitową liczbę całkowitą ze znakiem, wykorzystując podane informacje o formatowaniu.

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu znaków. |

### Wartość zwracana

16-bitowa liczba całkowita ze znakiem równa liczbie przedstawionej w określonym ciągu znaków.

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) metoda




```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podany ciąg znaków zawierający tekstową reprezentację liczby na równoważną 16-bitową liczbę całkowitą ze znakiem, wykorzystując podane informacje o formatowaniu oraz styl liczby.

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dopuszczalny styl tekstowej reprezentacji liczby. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu znaków. |

### Wartość zwracana

16-bitowa liczba całkowita ze znakiem równa liczbie przedstawionej w określonym ciągu znaków.

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Zobacz także

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int16](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)