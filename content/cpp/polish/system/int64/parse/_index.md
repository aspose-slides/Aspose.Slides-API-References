---
title: Parse()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 64-bitową liczbę całkowitą ze znakiem.
type: docs
weight: 1
url: /pl/system/int64/parse/
---
## Int64::Parse(const String\&) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static int64_t System::Int64::Parse(const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |

### Wartość zwracana

64-bitowa liczba całkowita ze znakiem równa liczbie reprezentowanej przez podany ciąg znaków.

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 64-bitową liczbę całkowitą ze znakiem, wykorzystując dostarczone informacje formatowania.

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu znaków. |

### Wartość zwracana

64-bitowa liczba całkowita ze znakiem równa liczbie reprezentowanej przez podany ciąg znaków.

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) metoda




```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 64-bitową liczbę całkowitą ze znakiem, wykorzystując dostarczone informacje formatowania oraz styl liczby.

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby w ciągu znaków. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu znaków. |

### Wartość zwracana

64-bitowa liczba całkowita ze znakiem równa liczbie reprezentowanej przez podany ciąg znaków.

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Zobacz także

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int64](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)