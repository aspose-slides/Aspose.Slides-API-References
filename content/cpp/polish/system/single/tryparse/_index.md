---
title: TryParse()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową pojedynczej precyzji.
type: docs
weight: 14
url: /pl/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) metoda


Konwertuje podany ciąg znaków zawierający reprezentację liczby do równoważnej wartości zmiennoprzecinkowej pojedynczej precyzji.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| result | **float**\& | Referencja do zmiennej typu single-precision floating-point, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

true jeśli konwersja się powiodła, w przeciwnym razie – false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) metoda


Konwertuje podany ciąg znaków zawierający reprezentację liczby do równoważnej wartości zmiennoprzecinkowej pojedynczej precyzji, używając podanych informacji o formatowaniu i stylu liczby.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby w ciągu znaków. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków. |
| result | **float**\& | Referencja do zmiennej typu single-precision floating-point, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

true jeśli konwersja się powiodła, w przeciwnym razie – false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) metoda




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) metoda




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) metoda




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
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