---
title: ToUInt32()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Konwertuje podaną wartość logiczną na równoważną 32-bitową liczbę całkowitą bez znaku.
type: docs
weight: 170
url: /pl/system/convert/touint32/
---
## Convert::ToUInt32(bool) metoda

Konwertuje podaną wartość logiczną na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```

## Convert::ToUInt32(uint8_t) metoda

Konwertuje podaną 8-bitową liczbę całkowitą bez znaku na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```

## Convert::ToUInt32(int8_t) metoda

Konwertuje podaną 8-bitową liczbę całkowitą ze znakiem na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```

## Convert::ToUInt32(uint16_t) metoda

Konwertuje podaną 16-bitową liczbę całkowitą bez znaku na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```

## Convert::ToUInt32(int16_t) metoda

Konwertuje podaną 16-bitową liczbę całkowitą ze znakiem na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```

## Convert::ToUInt32(uint32_t) metoda

Zwraca podaną 32-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```

## Convert::ToUInt32(int32_t) metoda

Konwertuje podaną 32-bitową liczbę całkowitą ze znakiem na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```

## Convert::ToUInt32(uint64_t) metoda

Konwertuje podaną 64-bitową liczbę całkowitą bez znaku na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```

## Convert::ToUInt32(int64_t) metoda

Konwertuje podaną 64-bitową liczbę całkowitą ze znakiem na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```

## Convert::ToUInt32(float) metoda

Konwertuje podaną liczbę zmiennoprzecinkową typu float na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```

## Convert::ToUInt32(double) metoda

Konwertuje podaną liczbę zmiennoprzecinkową typu double na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```

## Convert::ToUInt32(const Decimal\&) metoda

Konwertuje podaną liczbę dziesiętną na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```

## Convert::ToUInt32(char_t) metoda

Konwertuje podany znak Unicode na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```

## Convert::ToUInt32(DateTime) metoda

Konwersja nie jest obsługiwana. Zawsze wyrzuca InvalidCastException.

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```

## Convert::ToUInt32(std::nullptr_t) metoda

Konwertuje podany ciąg null na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```

### Wartość zwracana

Zero.

## Convert::ToUInt32(const char_t *) metoda

Konwertuje podany ciąg znaków C-string zawierający reprezentację liczby na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | C-string do konwersji |

### Wartość zwracana

32-bitowa liczba całkowita bez znaku równa liczbie przedstawionej w podanym ciągu znaków C-string

## Convert::ToUInt32(const String\&) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji |

### Wartość zwracana

32-bitowa liczba całkowita bez znaku równa liczbie przedstawionej w podanym ciągu

## Convert::ToUInt32(const String\&, int) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby w określonej podstawie na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji |
| from_base | int | Podstawa liczby reprezentowanej przez ciąg |

### Wartość zwracana

32-bitowa liczba całkowita bez znaku równa liczbie przedstawionej w podanym ciągu

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 32-bitową liczbę całkowitą bez znaku przy użyciu przekazanych informacji o formatowaniu.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu |

### Wartość zwracana

32-bitowa liczba całkowita bez znaku równa liczbie przedstawionej w podanym ciągu

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) metoda




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 32-bitową liczbę całkowitą bez znaku przy użyciu przekazanych informacji o formatowaniu i stylu liczby.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu |

### Wartość zwracana

32-bitowa liczba całkowita bez znaku równa liczbie przedstawionej w podanym ciągu

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda 




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda 




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) metoda 




```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podaną opakowaną wartość na równoważną 32-bitową liczbę całkowitą bez znaku.

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Wspólny wskaźnik do obiektu opakowującego wartość do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format ciągu używany, jeśli typ opakowanej wartości jest [String](../../string/) |

### Wartość zwracana

32-bitowa liczba całkowita bez znaku równoważna podanej opakowanej wartości

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [Decimal](../../decimal/)
* Klasa [DateTime](../../datetime/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Klasa [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)