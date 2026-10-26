---
title: ToByte()
second_title: Aspose.Slides dla C++ - Referencja API
description: Konwertuje określoną wartość logiczną na równoważną 8-bitową liczbę całkowitą bez znaku.
type: docs
weight: 92
url: /pl/system/convert/tobyte/
---
## Convert::ToByte(bool) metoda


Konwertuje określoną wartość logiczną na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) metoda


Zwraca określoną 8-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) metoda


Konwertuje określoną 8-bitową liczbę całkowitą ze znakiem na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) metoda


Konwertuje określoną 16-bitową liczbę całkowitą bez znaku na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) metoda


Konwertuje określoną 16-bitową liczbę całkowitą ze znakiem na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) metoda


Konwertuje określoną 32-bitową liczbę całkowitą bez znaku na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) metoda


Konwertuje określoną 32-bitową liczbę całkowitą ze znakiem na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) metoda


Konwertuje określoną 64-bitową liczbę całkowitą bez znaku na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) metoda


Konwertuje określoną 64-bitową liczbę całkowitą ze znakiem na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) metoda


Konwertuje określoną liczbę zmiennoprzecinkową typu float na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) metoda


Konwertuje określoną liczbę zmiennoprzecinkową typu double na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) metoda


Konwertuje określoną liczbę dziesiętną na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) metoda


Konwertuje określony znak Unicode na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) metoda


Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException.

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) metoda


Konwertuje określony null-string na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```


### Wartość zwracana

Zero.

## Convert::ToByte(const char_t *) metoda


Konwertuje określony ciąg znaków C zawierający reprezentację liczbową na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | C ciąg znaków C do konwersji |

### Wartość zwracana

8-bitowa liczba całkowita bez znaku równa liczbie reprezentowanej przez określony ciąg znaków C

## Convert::ToByte(const String\&) metoda


Konwertuje określony ciąg znaków zawierający reprezentację liczbową na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |

### Wartość zwracana

8-bitowa liczba całkowita bez znaku równa liczbie reprezentowanej przez określony ciąg znaków

## Convert::ToByte(const String\&, int) metoda


Konwertuje określony ciąg znaków zawierający reprezentację liczbową w podanej podstawie na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| from_base | int | Podstawa liczby reprezentowanej przez ciąg znaków |

### Wartość zwracana

8-bitowa liczba całkowita bez znaku równa liczbie reprezentowanej przez określony ciąg znaków

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje określony ciąg znaków zawierający reprezentację liczbową na równoważną 8-bitową liczbę całkowitą bez znaku przy użyciu podanych informacji formatowania.

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków |

### Wartość zwracana

8-bitowa liczba całkowita bez znaku równa liczbie reprezentowanej przez określony ciąg znaków

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) metoda




```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje określony ciąg znaków zawierający reprezentację liczbową na równoważną 8-bitową liczbę całkowitą bez znaku przy użyciu podanych informacji formatowania i stylu liczby.

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby w ciągu znaków |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków |

### Wartość zwracana

8-bitowa liczba całkowita bez znaku równa liczbie reprezentowanej przez określony ciąg znaków

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda 




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) metoda 




```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje określoną wartość opakowaną (boxed) na równoważną 8-bitową liczbę całkowitą bez znaku.

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Wskaźnik współdzielony na obiekt opakowujący wartość do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format ciągu znaków używany, jeśli typ opakowanej wartości jest [String](../../string/) |

### Wartość zwracana

8-bitowa liczba całkowita bez znaku równoważna określonej wartości opakowanej

## Zobacz także

* Wyliczenie [NumberStyles](../../../system.globalization/numberstyles/)
* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [Decimal](../../decimal/)
* Klasa [DateTime](../../datetime/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Klasa [Object](../../object/)
* Struktura [Convert](../)
* Struktura [Enum](../../enum/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)