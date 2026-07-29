---
title: ToDouble()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar det angivna booleska värdet till ett motsvarande dubbelprecision flyttal.
type: docs
weight: 222
url: /sv/system/convert/todouble/
---
## Convert::ToDouble(bool) metod


Konverterar det angivna booleska värdet till ett motsvarande dubbelprecision flyttal.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) metod


Konverterar den angivna 8-bit osignerade heltalet till ett motsvarande dubbelprecision flyttal.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) metod


Konverterar den angivna 8-bit signerade heltalet till ett motsvarande dubbelprecision flyttal.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) metod


Konverterar den angivna 16-bit osignerade heltalet till ett motsvarande dubbelprecision flyttal.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) metod


Konverterar den angivna 16-bit signerade heltalet till ett motsvarande dubbelprecision flyttal.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) metod


Konverterar den angivna 32-bit osignerade heltalet till ett motsvarande dubbelprecision flyttal.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) metod


Konverterar den angivna 32-bit signerade heltalet till ett motsvarande dubbelprecision flyttal.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) metod


Konverterar den angivna 64-bit osignerade heltalet till ett motsvarande dubbelprecision flyttal.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) metod


Konverterar den angivna 64-bit signerade heltalet till ett motsvarande dubbelprecision flyttal.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) metod


Konverterar det angivna enkelprecisionstalet till ett motsvarande dubbelprecision flyttal.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) metod


Returnerar det angivna dubbelvärdet.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) metod


Konverterar det angivna decimalvärdet till ett motsvarande dubbelprecision flyttal.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) metod


Konverterar den angivna null-strängen till motsvarande dubbelprecision flyttal.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### Returvärde

Noll.

## Convert::ToDouble(const char_t *) metod


Konverterar den angivna c-strängen som innehåller talrepresentationen till motsvarande dubbelprecision flyttal.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | c-strängen att konvertera |

### Returvärde

Det dubbelprecision flyttal som är lika med talet som representeras av den angivna c-strängen

## Convert::ToDouble(const String\&) metod


Konverterar den angivna strängen som innehåller talrepresentationen till motsvarande dubbelprecision flyttal.

```cpp
static double System::Convert::ToDouble(const String &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |

### Returvärde

Det dubbelprecision flyttal som är lika med talet som representeras av den angivna strängen

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar den angivna strängen som innehåller talrepresentationen till motsvarande dubbelprecision flyttal med den medföljande formateringsinformationen.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formatinformationen för strängen |

### Returvärde

Det dubbelprecision flyttal som är lika med talet som representeras av den angivna strängen

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) metod




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar den angivna strängen som innehåller talrepresentationen till motsvarande dubbelprecision flyttal med den medföljande formateringsinformationen och talstilen.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enum som anger tillåten stil för talrepresentationen |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formatinformationen för strängen |

### Returvärde

Det dubbelprecision flyttal som är lika med talet som representeras av den angivna strängen

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) metod




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar det angivna förpackade värdet till ett dubbelprecision flyttal. Om den förpackade värdets typ är [String](../../string/), används det angivna strängformatet under konverteringen.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Den delade pekaren till objektet som förpackar värdet att konvertera |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Strängformatet att använda om den förpackade värdets typ är [String](../../string/) |

### Returvärde

Ett dubbelprecision flyttal som är motsvarande det angivna förpackade värdet

## Se också

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [Decimal](../../decimal/)
* Klass [DateTime](../../datetime/)
* Klass [String](../../string/)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Klass [Object](../../object/)
* Struktur [Convert](../)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)