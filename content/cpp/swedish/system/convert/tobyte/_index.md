---
title: ToByte()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar det angivna boolska värdet till ett motsvarande 8-bitars osignerat heltal.
type: docs
weight: 92
url: /sv/system/convert/tobyte/
---
## Convert::ToByte(bool) metod

Konverterar det angivna boolska värdet till ett motsvarande 8-bitars osignerat heltal.

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) metod

Returnerar det angivna 8-bitars osignerade heltalet.

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) metod

Konverterar det angivna 8-bitars signerade heltalet till ett motsvarande 8-bitars osignerat heltal.

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) metod

Konverterar det angivna 16-bitars osignerade heltalet till ett motsvarande 8-bitars osignerat heltal.

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) metod

Konverterar det angivna 16-bitars signerade heltalet till ett motsvarande 8-bitars osignerat heltal.

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) metod

Konverterar det angivna 32-bitars osignerade heltalet till ett motsvarande 8-bitars osignerat heltal.

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) metod

Konverterar det angivna 32-bitars signerade heltalet till ett motsvarande 8-bitars osignerat heltal.

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) metod

Konverterar det angivna 64-bitars osignerade heltalet till ett motsvarande 8-bitars osignerat heltal.

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) metod

Konverterar det angivna 64-bitars signerade heltalet till ett motsvarande 8-bitars osignerat heltal.

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) metod

Konverterar det angivna flyttalet till ett motsvarande 8-bitars osignerat heltal.

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) metod

Konverterar det angivna dubbelprecisionstalet till ett motsvarande 8-bitars osignerat heltal.

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) metod

Konverterar det angivna decimaltalet till ett motsvarande 8-bitars osignerat heltal.

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) metod

Konverterar det angivna Unicode-tecknet till ett motsvarande 8-bitars osignerat heltal.

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) metod

Konverterar den angivna null-strängen till motsvarande osignerade 8-bitars heltalsvärde.

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```

### Returvärde

Noll.

## Convert::ToByte(const char_t *) metod

Konverterar den angivna c-strängen som innehåller en numerisk representation till motsvarande osignerade 8-bitars heltalsvärde.

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | c-strängen att konvertera |

### Returvärde

Det osignerade 8-bitars heltalsvärdet som motsvarar talet som representeras av den angivna c-strängen

## Convert::ToByte(const String\&) metod

Konverterar den angivna strängen som innehåller en numerisk representation till motsvarande osignerade 8-bitars heltalsvärde.

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |

### Returvärde

Det osignerade 8-bitars heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToByte(const String\&, int) metod

Konverterar den angivna strängen som innehåller en numerisk representation i den angivna basen till motsvarande osignerade 8-bitars heltalsvärde.

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| from_base | int | Basen för talet som representeras av strängen |

### Returvärde

Det osignerade 8-bitars heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller en numerisk representation till motsvarande osignerade 8-bitars heltalsvärde med hjälp av den angivna formateringsinformationen.

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formatinformationen för strängen |

### Returvärde

Det osignerade 8-bitars heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) metod




```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller en numerisk representation till motsvarande osignerade 8-bitars heltalsvärde med hjälp av den angivna formateringsinformationen och talstilen.

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden från NumberStyles-enumerationen som anger den tillåtna stilen för den numeriska representationen |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formatinformationen för strängen |

### Returvärde

Det osignerade 8-bitars heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) metod




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) metod




```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar det angivna inneslutna värdet till motsvarande osignerat 8-bitars heltalsvärde.

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Den delade pekaren till objektet som innesluter värdet som ska konverteras |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Den strängformat som ska användas om typen av det inneslutna värdet är [String](../../string/) |

### Returvärde

Ett osignerat 8-bitars heltalsvärde som motsvarar det angivna inneslutna värdet

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