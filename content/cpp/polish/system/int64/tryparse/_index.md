---
title: TryParse()
second_title: Odwołanie API Aspose.Slides dla C++
description: Konwertuje podany ciąg znaków zawierający reprezentację liczby w formie tekstowej na równoważną 64-bitową liczbę całkowitą ze znakiem.
type: docs
weight: 14
url: /pl/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) metoda


Konwertuje podany ciąg znaków zawierający reprezentację liczby w postaci tekstowej na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| result | **int64_t**\& | Referencja do zmiennej typu 64-bitowej liczby całkowitej ze znakiem, w której umieszczany jest wynik konwersji. |

### Wartość zwracana

True, jeśli konwersja się powiodła, w przeciwnym razie - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) metoda


Konwertuje podany ciąg znaków zawierający reprezentację liczby w postaci tekstowej na równoważną 64-bitową liczbę całkowitą ze znakiem przy użyciu dostarczonych informacji o formatowaniu i stylu liczby.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby w ciągu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu. |
| result | **int64_t**\& | Referencja do zmiennej typu 64-bitowej liczby całkowitej ze znakiem, w której umieszczany jest wynik konwersji. |

### Wartość zwracana

True, jeśli konwersja się powiodła, w przeciwnym razie - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) metoda




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) metoda




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) metoda




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Zobacz również

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [Int64](../)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)