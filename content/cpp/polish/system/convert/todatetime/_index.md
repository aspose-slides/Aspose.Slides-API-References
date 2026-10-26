---
title: ToDateTime()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException.
type: docs
weight: 248
url: /pl/system/convert/todatetime/
---
## Convert::ToDateTime(bool) metoda

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) metoda

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) metoda

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) metoda

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) metoda

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) metoda

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) metoda

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) metoda

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) metoda

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) metoda

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) metoda

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) metoda

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) metoda

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) metoda

Returns the specified date and time.

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) metoda

Converts the specified string to an instance of [DateTime](../../datetime/) class.

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |

### Wartość zwracana

Instancja klasy [DateTime](../../datetime/) reprezentująca informacje o dacie i czasie zawarte w podanym ciągu znaków

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Converts the specified string to an instance of [DateTime](../../datetime/) class using the provided formatting information.

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków |

### Wartość zwracana

Instancja klasy [DateTime](../../datetime/) reprezentująca informacje o dacie i czasie zawarte w podanym ciągu znaków

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) metoda




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) metoda




```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda

Converts the specified boxed value to equivalent [DateTime](../../datetime/) value.

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Współdzielony wskaźnik do obiektu zapakowującego wartość do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format ciągu znaków, który ma być użyty, jeśli typ zapakowanej wartości jest [String](../../string/) |

### Wartość zwracana

Wartość [DateTime](../../datetime/) równoważna podanej zapakowanej wartości

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [DateTime](../../datetime/)
* Klasa [Decimal](../../decimal/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Klasa [Object](../../object/)
* Struktura [Convert](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)