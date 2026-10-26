---
title: TryParse()
second_title: Aspose.Slides dla C++ - odniesienie do API
description: Konwertuje podany ciąg znaków zawierający tekstową reprezentację liczby na równoważną 8-bitową liczbę całkowitą bez znaku.
type: docs
weight: 14
url: /pl/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) metoda

Konwertuje podany ciąg znaków zawierający tekstową reprezentację liczby na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| result | **uint8_t**\& | Referencja do zmiennej 8-bitowej liczby całkowitej bez znaku, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

True jeśli konwersja się powiodła, w przeciwnym razie - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) metoda

Konwertuje podany ciąg znaków zawierający tekstową reprezentację liczby na równoważną 8-bitową liczbę całkowitą bez znaku, używając podanych informacji formatowania i stylu liczby.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dopuszczalny styl tekstowej reprezentacji liczby. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu. |
| result | **uint8_t**\& | Referencja do zmiennej 8-bitowej liczby całkowitej bez znaku, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

True jeśli konwersja się powiodła, w przeciwnym razie - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) metoda

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) metoda

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) metoda

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## Zobacz także

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)