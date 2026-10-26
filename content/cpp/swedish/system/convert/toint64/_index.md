---
title: ToInt64()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar det angivna boolska värdet till ett motsvarande 64-bitars signerat heltal.
type: docs
weight: 183
url: /sv/system/convert/toint64/
---
## Convert::ToInt64(bool) metod

Konverterar det angivna boolska värdet till ett motsvarande 64-bitars signerat heltal.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```

## Convert::ToInt64(uint8_t) metod

Konverterar den angivna 8-bitars osignerade heltalet till ett motsvarande 64-bitars signerat heltal.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```

## Convert::ToInt64(int8_t) metod

Konverterar den angivna 8-bitars signerade heltalet till ett motsvarande 64-bitars signerat heltal.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```

## Convert::ToInt64(uint16_t) metod

Konverterar den angivna 16-bitars osignerade heltalet till ett motsvarande 64-bitars signerat heltal.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```

## Convert::ToInt64(int16_t) metod

Konverterar den angivna 16-bitars signerade heltalet till ett motsvarande 64-bitars signerat heltal.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```

## Convert::ToInt64(uint32_t) metod

Konverterar den angivna 32-bitars osignerade heltalet till ett motsvarande 64-bitars signerat heltal.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```

## Convert::ToInt64(int32_t) metod

Konverterar den angivna 32-bitars signerade heltalet till ett motsvarande 64-bitars signerat heltal.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```

## Convert::ToInt64(uint64_t) metod

Konverterar den angivna 64-bitars osignerade heltalet till ett motsvarande 64-bitars signerat heltal.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```

## Convert::ToInt64(int64_t) metod

Returnerar det angivna 64-bitars signerade heltalet.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```

## Convert::ToInt64(float) metod

Konverterar det angivna flyttalet till ett motsvarande 64-bitars signerat heltal.

```cpp
static int64_t System::Convert::ToInt64(float value)
```

## Convert::ToInt64(double) metod

Konverterar det angivna dubbla talet till ett motsvarande 64-bitars signerat heltal.

```cpp
static int64_t System::Convert::ToInt64(double value)
```

## Convert::ToInt64(const Decimal\&) metod

Konverterar det angivna decimalvärdet till ett motsvarande 64-bitars signerat heltal.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```

## Convert::ToInt64(char_t) metod

Konverterar den angivna unicode-tecknet till ett motsvarande 64-bitars signerat heltal.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```

## Convert::ToInt64(DateTime) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```

## Convert::ToInt64(std::nullptr_t) metod

Konverterar den angivna null-strängen till motsvarande int-värde på 64-bit.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```

### Returvärde

Noll.

## Convert::ToInt64(const char_t *) metod

Konverterar den angivna c-strängen som innehåller talets teckenrepresentation till motsvarande 64-bitars heltalvärde.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | c-strängen att konvertera |

### Returvärde

Det 64-bitars heltalvärdet som är lika med talet som representeras av den angivna c-strängen

## Convert::ToInt64(const String\&) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 64-bitars heltalvärde.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |

### Returvärde

Det 64-bitars heltalvärdet som är lika med talet som representeras av den angivna strängen

## Convert::ToInt64(const String\&, int) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation i den angivna basen till motsvarande 64-bitars heltalvärde.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| from_base | int | Basen för talet som representeras av strängen |

### Returvärde

Det 64-bitars heltalvärdet som är lika med talet som representeras av den angivna strängen

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 64-bitars heltalvärde med den angivna formateringsinformationen.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formateringsinformationen för strängen |

### Returvärde

Det 64-bitars heltalvärdet som är lika med talet som representeras av den angivna strängen

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) metod




```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 64-bitars heltalvärde med den angivna formateringsinformationen och talstil.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enumerationen som anger vilken stil som tillåts för talets teckenrepresentation |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formateringsinformationen för strängen |

### Returvärde

Det 64-bitars heltalvärdet som är lika med talet som representeras av den angivna strängen

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) metod 




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) metod 




```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar det angivna kapslade värdet till motsvarande 64-bitars heltalvärde.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Den delade pekaren till objektet som kapslar värdet att konvertera |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formateringsinformationen att använda om den kapslade värdets typ är [String](../../string/) |

### Returvärde

Ett 64-bitars heltalvärde som motsvarar det angivna kapslade värdet

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)