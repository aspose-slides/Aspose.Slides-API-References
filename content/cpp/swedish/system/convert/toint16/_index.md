---
title: ToInt16()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar det angivna boolska värdet till ett motsvarande 16-bitars signerat heltal.
type: docs
weight: 131
url: /sv/system/convert/toint16/
---
## Convert::ToInt16(bool) metod

Konverterar det angivna boolska värdet till ett motsvarande 16-bitars signerat heltal.

```cpp
static constexpr int16_t System::Convert::ToInt16(bool value)
```

## Convert::ToInt16(uint8_t) metod

Konverterar det angivna 8-bitars osignerade heltalet till ett motsvarande 16-bitars signerat heltal.

```cpp
static constexpr int16_t System::Convert::ToInt16(uint8_t value)
```

## Convert::ToInt16(int8_t) metod

Konverterar det angivna 8-bitars signerade heltalet till ett motsvarande 16-bitars signerat heltal.

```cpp
static constexpr int16_t System::Convert::ToInt16(int8_t value)
```

## Convert::ToInt16(uint16_t) metod

Konverterar det angivna 16-bitars osignerade heltalet till ett motsvarande 16-bitars signerat heltal.

```cpp
static int16_t System::Convert::ToInt16(uint16_t value)
```

## Convert::ToInt16(int16_t) metod

Returnerar det angivna 16-bitars signerade heltalet.

```cpp
static constexpr int16_t System::Convert::ToInt16(int16_t value)
```

## Convert::ToInt16(uint32_t) metod

Konverterar det angivna 32-bitars osignerade heltalet till ett motsvarande 16-bitars signerat heltal.

```cpp
static int16_t System::Convert::ToInt16(uint32_t value)
```

## Convert::ToInt16(int32_t) metod

Konverterar det angivna 32-bitars signerade heltalet till ett motsvarande 16-bitars signerat heltal.

```cpp
static int16_t System::Convert::ToInt16(int32_t value)
```

## Convert::ToInt16(uint64_t) metod

Konverterar det angivna 64-bitars osignerade heltalet till ett motsvarande 16-bitars signerat heltal.

```cpp
static int16_t System::Convert::ToInt16(uint64_t value)
```

## Convert::ToInt16(int64_t) metod

Konverterar det angivna 64-bitars signerade heltalet till ett motsvarande 16-bitars signerat heltal.

```cpp
static int16_t System::Convert::ToInt16(int64_t value)
```

## Convert::ToInt16(float) metod

Konverterar det angivna float-värdet till ett motsvarande 16-bitars signerat heltal.

```cpp
static int16_t System::Convert::ToInt16(float value)
```

## Convert::ToInt16(double) metod

Konverterar det angivna double-värdet till ett motsvarande 16-bitars signerat heltal.

```cpp
static int16_t System::Convert::ToInt16(double value)
```

## Convert::ToInt16(const Decimal\&) metod

Konverterar det angivna decimal-värdet till ett motsvarande 16-bitars signerat heltal.

```cpp
static int16_t System::Convert::ToInt16(const Decimal &value)
```

## Convert::ToInt16(char_t) metod

Konverterar det angivna Unicode-tecknet till ett motsvarande 16-bitars signerat heltal.

```cpp
static int16_t System::Convert::ToInt16(char_t value)
```

## Convert::ToInt16(DateTime) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static int16_t System::Convert::ToInt16(DateTime value)
```

## Convert::ToInt16(std::nullptr_t) metod

Konverterar den angivna null-strängen till motsvarande 16-bitars heltalsvärde.

```cpp
static constexpr int16_t System::Convert::ToInt16(std::nullptr_t)
```

### Returvärde

Noll.

## Convert::ToInt16(const char_t *) metod

Konverterar den angivna c-strängen som innehåller en talrepresentation till motsvarande 16-bitars heltalsvärde.

```cpp
static int16_t System::Convert::ToInt16(const char_t *value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | c-strängen att konvertera |

### Returvärde

Det 16-bitars heltalsvärdet som motsvarar talet som representeras av den angivna c-strängen

## Convert::ToInt16(const String\&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 16-bitars heltalsvärde.

```cpp
static int16_t System::Convert::ToInt16(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |

### Returvärde

Det 16-bitars heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToInt16(const String\&, int) metod

Konverterar den angivna strängen som innehåller talets textrepresentation i den angivna basen till motsvarande 16-bitars heltalsvärde.

```cpp
static int16_t System::Convert::ToInt16(const String &value, int from_base)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| from_base | int | Basen för talet som representeras av strängen |

### Returvärde

Det 16-bitars heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 16-bitars heltalsvärde med hjälp av den angivna formateringsinformationen.

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller information om strängformat |

### Returvärde

Det 16-bitars heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, std::nullptr_t) metod

```cpp
static int16_t System::Convert::ToInt16(const String &value, std::nullptr_t)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 16-bitars heltalsvärde med hjälp av den angivna formateringsinformationen och talstilen.

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden från NumberStyles-enumerationen som anger tillåten stil för talets textrepresentation |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller information om strängformat |

### Returvärde

Det 16-bitars heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) metod

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt16(Enum) metod

```cpp
template<typename Enum,typename> static int16_t System::Convert::ToInt16(Enum value)
```

## Convert::ToInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar det angivna inlåsta värdet till ett motsvarande 16-bitars heltalsvärde.

```cpp
static int16_t System::Convert::ToInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Den delade pekaren till objektet som kapslar in värdet som ska konverteras |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Strängformatet som ska användas om den inlåsta värdetypen är [String](../../string/) |

### Returvärde

Ett 16-bitars heltalsvärde som motsvarar det angivna inlåsta värdet

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