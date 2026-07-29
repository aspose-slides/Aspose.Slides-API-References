---
title: ToDateTime()
second_title: Aspose.Slides för C++ API-referens
description: Konvertering stöds inte. Kastar alltid InvalidCastException.
type: docs
weight: 248
url: /sv/system/convert/todatetime/
---
## Convert::ToDateTime(bool) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) metod

Returnerar det angivna datumet och tiden.

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) metod

Konverterar den angivna strängen till en instans av klassen [DateTime](../../datetime/).

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras |

### Returvärde

En instans av klassen [DateTime](../../datetime/) som representerar datum- och tidsinformationen som den angivna strängen representerar

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen till en instans av klassen [DateTime](../../datetime/) med hjälp av den angivna formateringsinformationen.

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller strängformatinformationen |

### Returvärde

En instans av klassen [DateTime](../../datetime/) som representerar datum- och tidsinformationen som den angivna strängen representerar

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod



```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) metod



```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) metod



```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar det angivna inpackade värdet till ett motsvarande [DateTime](../../datetime/)-värde.

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Den delade pekaren till objektet som kapslar in värdet som ska konverteras |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Strängformatet som ska användas om typen av det inpackade värdet är [String](../../string/) |

### Returvärde

Ett [DateTime](../../datetime/)-värde som är motsvarande det angivna inpackade värdet

## Se även

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