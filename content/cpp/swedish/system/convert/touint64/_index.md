---
title: ToUInt64()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar det angivna boolska värdet till ett motsvarande 64-bit osignerat heltal.
type: docs
weight: 196
url: /sv/system/convert/touint64/
---
## Convert::ToUInt64(bool) metod


Konverterar det angivna boolska värdet till ett motsvarande 64-bit osignerat heltal.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(bool value)
```

## Convert::ToUInt64(uint8_t) metod


Konverterar det angivna 8-bit osignerade heltalet till ett motsvarande 64-bit osignerat heltal.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint8_t value)
```

## Convert::ToUInt64(int8_t) metod


Konverterar det angivna 8-bit signerade heltalet till ett motsvarande 64-bit osignerat heltal.

```cpp
static uint64_t System::Convert::ToUInt64(int8_t value)
```

## Convert::ToUInt64(uint16_t) metod


Konverterar det angivna 16-bit osignerade heltalet till ett motsvarande 64-bit osignerat heltal.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint16_t value)
```

## Convert::ToUInt64(int16_t) metod


Konverterar det angivna 16-bit signerade heltalet till ett motsvarande 64-bit osignerat heltal.

```cpp
static uint64_t System::Convert::ToUInt64(int16_t value)
```

## Convert::ToUInt64(uint32_t) metod


Konverterar det angivna 32-bit osignerade heltalet till ett motsvarande 64-bit osignerat heltal.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint32_t value)
```

## Convert::ToUInt64(int32_t) metod


Konverterar det angivna 32-bit signerade heltalet till ett motsvarande 64-bit osignerat heltal.

```cpp
static uint64_t System::Convert::ToUInt64(int32_t value)
```

## Convert::ToUInt64(uint64_t) metod


Returnerar det angivna 64-bit osignerade heltalet.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint64_t value)
```

## Convert::ToUInt64(int64_t) metod


Konverterar det angivna 64-bit signerade heltalet till ett motsvarande 64-bit osignerat heltal.

```cpp
static uint64_t System::Convert::ToUInt64(int64_t value)
```

## Convert::ToUInt64(float) metod


Konverterar det angivna flyttalet till ett motsvarande 64-bit osignerat heltal.

```cpp
static uint64_t System::Convert::ToUInt64(float value)
```

## Convert::ToUInt64(double) metod


Konverterar det angivna dubbelvärdet till ett motsvarande 64-bit osignerat heltal.

```cpp
static uint64_t System::Convert::ToUInt64(double value)
```

## Convert::ToUInt64(const Decimal\&) metod


Konverterar det angivna decimalvärdet till ett motsvarande 64-bit osignerat heltal.

```cpp
static uint64_t System::Convert::ToUInt64(const Decimal &value)
```

## Convert::ToUInt64(char_t) metod


Konverterar det angivna Unicode-tecknet till ett motsvarande 64-bit osignerat heltal.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(char_t value)
```

## Convert::ToUInt64(DateTime) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static uint64_t System::Convert::ToUInt64(DateTime value)
```

## Convert::ToUInt64(std::nullptr_t) metod


Konverterar den angivna null-strängen till motsvarande osignerade 64-bit heltalsvärde.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(std::nullptr_t)
```


### Returvärde

Noll.

## Convert::ToUInt64(const char_t *) metod


Konverterar den angivna c-strängen som innehåller en talrepresentation till motsvarande osignerade 64-bit heltalsvärde.

```cpp
static uint64_t System::Convert::ToUInt64(const char_t *value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | c-strängen som ska konverteras |

### Returvärde

Det osignerade 64-bit heltalsvärdet som motsvarar talet som representeras av den angivna c-strängen

## Convert::ToUInt64(const String\&) metod


Konverterar den angivna strängen som innehåller en talrepresentation till motsvarande osignerade 64-bit heltalsvärde.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras |

### Returvärde

Det osignerade 64-bit heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToUInt64(const String\&, int) metod


Konverterar den angivna strängen som innehåller en talrepresentation i den angivna basen till motsvarande osignerade 64-bit heltalsvärde.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, int from_base)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras |
| from_base | int | Basen för talet som representeras av strängen |

### Returvärde

Det osignerade 64-bit heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToUInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar den angivna strängen som innehåller en talrepresentation till motsvarande osignerade 64-bit heltalsvärde med den angivna formateringsinformationen.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller information om strängformatet |

### Returvärde

Det osignerade 64-bit heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, std::nullptr_t) metod




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, std::nullptr_t)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar den angivna strängen som innehåller en talrepresentation till motsvarande osignerade 64-bit heltalsvärde med den angivna formateringsinformationen och talstil.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enumerationen som specificerar den tillåtna stilen för talrepresentationen i strängen |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller information om strängformatet |

### Returvärde

Det osignerade 64-bit heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) metod




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt64(Enum) metod




```cpp
template<typename Enum,typename> static uint64_t System::Convert::ToUInt64(Enum value)
```

## Convert::ToUInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar det angivna inlåsta värdet till motsvarande osignerat 64-bit heltal.

```cpp
static uint64_t System::Convert::ToUInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Delad pekare till objektet som kapslar värdet som ska konverteras |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Strängformatet som ska användas om typen av det inlåsta värdet är [String](../../string/) |

### Returvärde

Ett osignerat 64-bit heltalsvärde som är motsvarande det angivna inlåsta värdet

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