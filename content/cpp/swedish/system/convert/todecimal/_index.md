---
title: ToDecimal()
second_title: Aspose.Slides för C++ API-referens
description: Omvandlar det angivna boolska värdet till ett motsvarande decimaltal.
type: docs
weight: 235
url: /sv/system/convert/todecimal/
---
## Convert::ToDecimal(bool) metod


Omvandlar det angivna boolska värdet till ett motsvarande decimaltal.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) metod


Omvandlar det angivna 8-bit osignerade heltalet till ett motsvarande decimaltal.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) metod


Omvandlar det angivna 8-bit signerade heltalet till ett motsvarande decimaltal.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) metod


Omvandlar det angivna 16-bit osignerade heltalet till ett motsvarande decimaltal.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) metod


Omvandlar det angivna 16-bit signerade heltalet till ett motsvarande decimaltal.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) metod


Omvandlar det angivna 32-bit osignerade heltalet till ett motsvarande decimaltal.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) metod


Omvandlar det angivna 32-bit signerade heltalet till ett motsvarande decimaltal.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) metod


Omvandlar det angivna 64-bit osignerade heltalet till ett motsvarande decimaltal.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) metod


Omvandlar det angivna 64-bit signerade heltalet till ett motsvarande decimaltal.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) metod


Omvandlar det angivna flyttalsvärdet till ett motsvarande decimaltal.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) metod


Omvandlar det angivna dubblvärdet till ett motsvarande decimaltal.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) metod


Returnerar det angivna decimalvärdet.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) metod


Omvandlar den angivna null-strängen till motsvarande [Decimal](../../decimal/) värde.

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```


### Returvärde

Noll.

## Convert::ToDecimal(const char_t *) metod


Omvandlar den angivna c-strängen som innehåller en talrepresentation till motsvarande [Decimal](../../decimal/) värde.

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | c-strängen att konvertera |

### Returvärde

Det [Decimal](../../decimal/) värde som är lika med talet som representeras av den angivna c-strängen

## Convert::ToDecimal(const String\&) metod


Omvandlar den angivna strängen som innehåller en talrepresentation till motsvarande [Decimal](../../decimal/) värde.

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |

### Returvärde

Det [Decimal](../../decimal/) värde som är lika med talet som representeras av den angivna strängen

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) metod


Omvandlar den angivna strängen som innehåller en talrepresentation till motsvarande [Decimal](../../decimal/) värde med den angivna formateringsinformationen.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formatinformationen för strängen |

### Returvärde

Det [Decimal](../../decimal/) värde som är lika med talet som representeras av den angivna strängen

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod


Omvandlar den angivna strängen som innehåller en talrepresentation till motsvarande [Decimal](../../decimal/) värde med de angivna talstilarna och formateringsinformationen.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i enumerationen NumberStyles som anger vilken stil som får användas för talrepresentationen |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formatinformationen för strängen |

### Returvärde

Det [Decimal](../../decimal/) värde som är lika med talet som representeras av den angivna strängen

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod


Omvandlar det angivna inlindade värdet till motsvarande [Decimal](../../decimal/) värde.

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Den delade pekaren till objektet som innehåller värdet som ska konverteras |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatsträngen som ska användas om den inlindade värdetypen är [String](../../string/) |

### Returvärde

Ett [Decimal](../../decimal/) värde som motsvarar det angivna inlindade värdet

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)