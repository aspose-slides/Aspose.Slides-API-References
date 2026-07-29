---
title: ToInt32()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar det angivna booleska värdet till ett motsvarande 32-bit signerat heltal.
type: docs
weight: 157
url: /sv/system/convert/toint32/
---
## Convert::ToInt32(bool) metod

Konverterar det angivna booleska värdet till ett motsvarande 32-bit signerat heltal.

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```
## Convert::ToInt32(uint8_t) metod

Konverterar det angivna 8-bit osignerade heltalet till ett motsvarande 32-bit signerat heltal.

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```
## Convert::ToInt32(int8_t) metod

Konverterar det angivna 8-bit signerade heltalet till ett motsvarande 32-bit signerat heltal.

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```
## Convert::ToInt32(uint16_t) metod

Konverterar det angivna 16-bit osignerade heltalet till ett motsvarande 32-bit signerat heltal.

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```
## Convert::ToInt32(int16_t) metod

Konverterar det angivna 16-bit signerade heltalet till ett motsvarande 32-bit signerat heltal.

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```
## Convert::ToInt32(uint32_t) metod

Konverterar det angivna 32-bit osignerade heltalet till ett motsvarande 32-bit signerat heltal.

```cpp
static int System::Convert::ToInt32(uint32_t value)
```
## Convert::ToInt32(int32_t) metod

Returnerar det angivna 32-bit signerade heltalet.

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```
## Convert::ToInt32(uint64_t) metod

Konverterar det angivna 64-bit osignerade heltalet till ett motsvarande 32-bit signerat heltal.

```cpp
static int System::Convert::ToInt32(uint64_t value)
```
## Convert::ToInt32(int64_t) metod

Konverterar det angivna 64-bit signerade heltalet till ett motsvarande 32-bit signerat heltal.

```cpp
static int System::Convert::ToInt32(int64_t value)
```
## Convert::ToInt32(float) metod

Konverterar det angivna flyttalet till ett motsvarande 32-bit signerat heltal.

```cpp
static int System::Convert::ToInt32(float value)
```
## Convert::ToInt32(double) metod

Konverterar det angivna dubbelprecisionstalet till ett motsvarande 32-bit signerat heltal.

```cpp
static int System::Convert::ToInt32(double value)
```
## Convert::ToInt32(const Decimal\&) metod

Konverterar det angivna decimaltalet till ett motsvarande 32-bit signerat heltal.

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```
## Convert::ToInt32(char_t) metod

Konverterar den angivna Unicode-tecknet till ett motsvarande 32-bit signerat heltal.

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```
## Convert::ToInt32(DateTime) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static int System::Convert::ToInt32(DateTime value)
```
## Convert::ToInt32(std::nullptr_t) metod

Konverterar den angivna null-strängen till motsvarande 32-bit heltalsvärde.

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```

### Return Value

Noll.

## Convert::ToInt32(const char_t *) metod

Konverterar den angivna c-strängen som innehåller talets textrepresentation till motsvarande 32-bit heltalsvärde.

```cpp
static int System::Convert::ToInt32(const char_t *value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | C-strängen att konvertera |

### Return Value

Det 32-bit heltalet som är lika med det tal som representeras av den angivna c-strängen

## Convert::ToInt32(const String\&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 32-bit heltalsvärde.

```cpp
static int System::Convert::ToInt32(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |

### Return Value

Det 32-bit heltalet som är lika med det tal som representeras av den angivna strängen

## Convert::ToInt32(const String\&, int) metod

Konverterar den angivna strängen som innehåller talets textrepresentation i den angivna basen till motsvarande 32-bit heltalsvärde.

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| from_base | int | Basen för talet som representeras av strängen |

### Return Value

Det 32-bit heltalet som är lika med det tal som representeras av den angivna strängen

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 32-bit heltalsvärde med den angivna formateringsinformationen.

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller strängformatinformationen |

### Return Value

Det 32-bit heltalet som är lika med det tal som representeras av den angivna strängen

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) metod




```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 32-bit heltalsvärde med den angivna formateringsinformationen och talstil.

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enum som specificerar den tillåtna stilen för talets textrepresentation |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller strängformatinformationen |

### Return Value

Det 32-bit heltalet som är lika med det tal som representeras av den angivna strängen

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) metod 




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) metod 




```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar det angivna boxade värdet till motsvarande 32-bit heltalsvärde.

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Den delade pekaren till objektet som boxar värdet som ska konverteras |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Strängformatet som ska användas om den boxade värdestypen är [String](../../string/) |

### Return Value

Ett 32-bit heltal som är motsvarande det angivna boxade värdet

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