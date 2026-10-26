---
title: ToDateTime()
second_title: Aspose.Slides pro C++ API Reference
description: Převod není podporován. Vždy vyvolá InvalidCastException.
type: docs
weight: 248
url: /cs/system/convert/todatetime/
---
## Convert::ToDateTime(bool) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) metoda

Vrací zadané datum a čas.

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) metoda

Převádí zadaný řetězec na instanci třídy [DateTime](../../datetime/).

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |

### Návratová hodnota

Instance třídy [DateTime](../../datetime/) představující datum a čas získané ze zadaného řetězce

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí zadaný řetězec na instanci třídy [DateTime](../../datetime/) pomocí poskytnutých informací o formátování.

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt obsahující informace o formátu řetězce |

### Návratová hodnota

Instance třídy [DateTime](../../datetime/) představující datum a čas získané ze zadaného řetězce

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

Převádí zadanou zabalovanou hodnotu na ekvivalentní hodnotu [DateTime](../../datetime/).

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt, který zabaluje hodnotu k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zabalené hodnoty [String](../../string/) |

### Návratová hodnota

Hodnota [DateTime](../../datetime/) ekvivalentní zadané zabalené hodnotě

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../../datetime/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)