---
title: Parse()
second_title: Odwołanie API Aspose.Slides dla C++
description: Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji.
type: docs
weight: 1
url: /pl/system/double/parse/
---
## Double::Parse(const String\&) metoda


Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji.

```cpp
static double System::Double::Parse(const String &value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |

### Wartość zwracana

Wartość zmiennoprzecinkowa podwójnej precyzji równa liczbie przedstawionej w podanym ciągu znaków.

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji przy użyciu podanych informacji formatowania.

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu znaków. |

### Wartość zwracana

Wartość zmiennoprzecinkowa podwójnej precyzji równa liczbie przedstawionej w podanym ciągu znaków.

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) metoda




```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji przy użyciu podanych informacji formatowania i stylu liczby.

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby w ciągu znaków. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu znaków. |

### Wartość zwracana

Wartość zmiennoprzecinkowa podwójnej precyzji równa liczbie przedstawionej w podanym ciągu znaków.

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda 




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Zobacz również

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)