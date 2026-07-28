---
title: TryParse()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 32-bitową liczbę całkowitą ze znakiem.
type: docs
weight: 14
url: /pl/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| result | **int32_t**\& | Referencja do zmiennej typu 32-bitowa liczba całkowita ze znakiem, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

True, jeśli konwersja się powiodła, w przeciwnym razie - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 32-bitową liczbę całkowitą ze znakiem, wykorzystując podane informacje formatowania i styl liczby.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby w ciągu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu. |
| result | **int32_t**\& | Referencja do zmiennej typu 32-bitowa liczba całkowita ze znakiem, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

True, jeśli konwersja się powiodła, w przeciwnym razie - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) metoda

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) metoda

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) metoda

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## Zobacz także

* Wyliczenie [NumberStyles](../../../system.globalization/numberstyles/)
* DefinicjaTypu [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [Int32](../)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* PrzestrzeńNazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)