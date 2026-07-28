---
title: TryParse()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Konwertuje określony ciąg znaków zawierający reprezentację liczby w formie tekstowej na równoważną 64-bitową liczbę całkowitą bez znaku.
type: docs
weight: 14
url: /pl/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) metoda


Konwertuje określony ciąg znaków zawierający reprezentację liczby w formie tekstowej na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| result | **uint64_t**\& | Referencja do zmiennej typu 64-bitowej liczby całkowitej bez znaku, w której zostaje umieszczony wynik konwersji. |

### Wartość zwracana

True if the conversion succeeded, otherwise - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) metoda


Konwertuje określony ciąg znaków zawierający reprezentację liczby w formie tekstowej na równoważną 64-bitową liczbę całkowitą bez znaku, używając podanych informacji o formatowaniu i stylu liczby.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl tekstowej reprezentacji liczby. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków. |
| result | **uint64_t**\& | Referencja do zmiennej typu 64-bitowej liczby całkowitej bez znaku, w której zostaje umieszczony wynik konwersji. |

### Wartość zwracana

True if the conversion succeeded, otherwise - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) metoda




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) metoda




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) metoda 




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## Zobacz także

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)