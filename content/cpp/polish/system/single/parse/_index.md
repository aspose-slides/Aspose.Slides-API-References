---
title: Parse()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową pojedynczej precyzji.
type: docs
weight: 1
url: /pl/system/single/parse/
---
## Single::Parse(const String\&) metoda


Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową pojedynczej precyzji.

```cpp
static float System::Single::Parse(const String &value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |

### Wartość zwracana

Wartość zmiennoprzecinkowa pojedynczej precyzji równa liczbie przedstawionej w podanym ciągu.

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową pojedynczej precyzji przy użyciu podanych informacji o formatowaniu.

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu. |

### Wartość zwracana

Wartość zmiennoprzecinkowa pojedynczej precyzji równa liczbie przedstawionej w podanym ciągu.

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) metoda




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową pojedynczej precyzji przy użyciu podanych informacji o formatowaniu i stylu liczby.

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby w ciągu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu. |

### Wartość zwracana

Wartość zmiennoprzecinkowa pojedynczej precyzji równa liczbie przedstawionej w podanym ciągu.

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Zobacz także

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)