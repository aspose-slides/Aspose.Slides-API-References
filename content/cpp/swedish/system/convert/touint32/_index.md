---
title: ToUInt32()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar det angivna booleska värdet till ett motsvarande 32-bit osignerat heltal.
type: docs
weight: 170
url: /sv/system/convert/touint32/
---
## Convert::ToUInt32(bool) metod

Konverterar det angivna booleska värdet till ett motsvarande 32-bit osignerat heltal.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```

## Convert::ToUInt32(uint8_t) metod

Konverterar det angivna 8-bit osignerade heltalet till ett motsvarande 32-bit osignerat heltal.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```

## Convert::ToUInt32(int8_t) metod

Konverterar det angivna 8-bit signerade heltalet till ett motsvarande 32-bit osignerat heltal.

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```

## Convert::ToUInt32(uint16_t) metod

Konverterar det angivna 16-bit osignerade heltalet till ett motsvarande 32-bit osignerat heltal.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```

## Convert::ToUInt32(int16_t) metod

Konverterar det angivna 16-bit signerade heltalet till ett motsvarande 32-bit osignerat heltal.

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```

## Convert::ToUInt32(uint32_t) metod

Returnerar det angivna 32-bit osignerade heltalet.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```

## Convert::ToUInt32(int32_t) metod

Konverterar det angivna 32-bit signerade heltalet till ett motsvarande 32-bit osignerat heltal.

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```

## Convert::ToUInt32(uint64_t) metod

Konverterar det angivna 64-bit osignerade heltalet till ett motsvarande 32-bit osignerat heltal.

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```

## Convert::ToUInt32(int64_t) metod

Konverterar det angivna 64-bit signerade heltalet till ett motsvarande 32-bit osignerat heltal.

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```

## Convert::ToUInt32(float) metod

Konverterar det angivna flyttalvärdet till ett motsvarande 32-bit osignerat heltal.

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```

## Convert::ToUInt32(double) metod

Konverterar det angivna dubbelvärdet till ett motsvarande 32-bit osignerat heltal.

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```

## Convert::ToUInt32(const Decimal\&) metod

Konverterar det angivna decimalvärdet till ett motsvarande 32-bit osignerat heltal.

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```

## Convert::ToUInt32(char_t) metod

Konverterar det angivna unicode-tecknet till ett motsvarande 32-bit osignerat heltal.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```

## Convert::ToUInt32(DateTime) metod

Konverteringen stöds inte. Kastar alltid InvalidCastException.

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```

## Convert::ToUInt32(std::nullptr_t) metod

Konverterar den angivna null-strängen till motsvarande osignerade 32-bit heltalsvärde.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```

### Returvärde

Noll.

## Convert::ToUInt32(const char_t *) metod

Konverterar den angivna c-strängen som innehåller talets teckenrepresentation till motsvarande osignerade 32-bit heltalsvärde.

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | c-strängen att konvertera |

### Returvärde

Det osignerade 32-bit heltalsvärdet som motsvarar talet som representeras av den angivna c-strängen

## Convert::ToUInt32(const String\&) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande osignerade 32-bit heltalsvärde.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |

### Returvärde

Det osignerade 32-bit heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToUInt32(const String\&, int) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation i den angivna basen till motsvarande osignerade 32-bit heltalsvärde.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| from_base | int | Basen för talet som representeras av strängen |

### Returvärde

Det osignerade 32-bit heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande osignerade 32-bit heltalsvärde med den angivna formateringsinformationen.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller information om strängformatet |

### Returvärde

Det osignerade 32-bit heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) metod

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande osignerade 32-bit heltalsvärde med den angivna formateringsinformationen och talstilen.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enumerationen som anger den tillåtna stilen för talets teckenrepresentation |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller information om strängformatet |

### Returvärde

Det osignerade 32-bit heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) metod

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) metod

```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar det angivna låsta värdet till ett motsvarande osignerat 32-bit heltal.

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Den delade pekaren till objektet som kapslar in värdet som ska konverteras |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Strängformatet som ska användas om typen av det kapslade värdet är [String](../../string/) |

### Returvärde

Ett osignerat 32-bit heltalsvärde som motsvarar det angivna kapslade värdet

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* klass [Decimal](../../decimal/)
* klass [DateTime](../../datetime/)
* klass [String](../../string/)
* klass [IFormatProvider](../../iformatprovider/)
* klass [CultureInfo](../../../system.globalization/cultureinfo/)
* klass [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* klass [Object](../../object/)
* struct [Convert](../)
* struct [Enum](../../enum/)
* namnrymd [System](../../)
* bibliotek [Aspose.Slides](../../../)