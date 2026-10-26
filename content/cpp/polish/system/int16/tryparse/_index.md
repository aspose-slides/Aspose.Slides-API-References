---
title: TryParse()
second_title: Aspose.Slides dla C++ – referencja API
description: Konwertuje określony ciąg zawierający reprezentację liczby w postaci tekstowej na równoważną 16-bitową liczbę całkowitą ze znakiem.
type: docs
weight: 14
url: /pl/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) metoda


Konwertuje określony ciąg zawierający reprezentację liczby w postaci tekstowej na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji. |
| result | **int16_t**\& | Referencja do zmiennej 16-bitowej liczby całkowitej ze znakiem, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

True jeśli konwersja powiodła się, w przeciwnym razie - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) metoda


Konwertuje określony ciąg zawierający reprezentację liczby w postaci tekstowej na równoważną 16-bitową liczbę całkowitą ze znakiem, używając podanych informacji formatowania i stylu liczby.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby w ciągu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu. |
| result | **int16_t**\& | Referencja do zmiennej 16-bitowej liczby całkowitej ze znakiem, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

True jeśli konwersja powiodła się, w przeciwnym razie - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) metoda




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) metoda




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) metoda




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
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