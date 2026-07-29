---
title: ToSByte()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar det angivna booleska värdet till ett motsvarande 8-bitars signerat heltal.
type: docs
weight: 105
url: /sv/system/convert/tosbyte/
---
## Convert::ToSByte(bool) metod

Konverterar det angivna booleska värdet till ett motsvarande 8-bitars signerat heltal.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) metod

Konverterar det angivna 8-bitars osignerade heltalet till ett motsvarande 8-bitars signerat heltal.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) metod

Returnerar det angivna 8-bitars signerade heltalet.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) metod

Konverterar det angivna 16-bitars osignerade heltalet till ett motsvarande 8-bitars signerat heltal.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) metod

Konverterar det angivna 16-bitars signerade heltalet till ett motsvarande 8-bitars signerat heltal.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) metod

Konverterar det angivna 32-bitars osignerade heltalet till ett motsvarande 8-bitars signerat heltal.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) metod

Konverterar det angivna 32-bitars signerade heltalet till ett motsvarande 8-bitars signerat heltal.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) metod

Konverterar det angivna 64-bitars osignerade heltalet till ett motsvarande 8-bitars signerat heltal.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) metod

Konverterar det angivna 64-bitars signerade heltalet till ett motsvarande 8-bitars signerat heltal.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) metod

Konverterar det angivna flyttal till ett motsvarande 8-bitars signerat heltal.

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) metod

Konverterar det angivna dubbelprecisionstal till ett motsvarande 8-bitars signerat heltal.

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal&) metod

Konverterar det angivna decimaltalet till ett motsvarande 8-bitars signerat heltal.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) metod

Konverterar det angivna Unicode-tecknet till ett motsvarande 8-bitars signerat heltal.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) metod

Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

## Convert::ToSByte(std::nullptr_t) metod

Konverterar den angivna null-strängen till motsvarande 8-bitars heltalsvärde.

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```

### Returvärde

Noll.

## Convert::ToSByte(const char_t *) metod

Konverterar den angivna c-stringen som innehåller talets textrepresentation till motsvarande 8-bitars heltalsvärde.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | c-string som ska konverteras |

### Returvärde

Det 8-bitars heltalsvärdet som motsvarar talet som representeras av den angivna c-stringen

## Convert::ToSByte(const String&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 8-bitars heltalsvärde.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras |

### Returvärde

Det 8-bitars heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToSByte(const String&, int) metod

Konverterar den angivna strängen som innehåller talets textrepresentation i den angivna basen till motsvarande 8-bitars heltalsvärde.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras |
| from_base | int | Basen för talet som representeras av strängen |

### Returvärde

Det 8-bitars heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToSByte(const String&, const SharedPtr<IFormatProvider>&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande osignerade 8-bitars heltalsvärde med hjälp av den angivna formateringsinformationen.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>\& | En pekare till ett objekt som innehåller strängformatinformationen |

### Returvärde

Det 8-bitars heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToSByte(const String&, const SharedPtr<Globalization::CultureInfo>&) metod

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String&, const SharedPtr<Globalization::NumberFormatInfo>&) metod

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String&, std::nullptr_t) metod

```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String&, Globalization::NumberStyles, const SharedPtr<IFormatProvider>&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 8-bitars heltalsvärde med den angivna formateringsinformationen och talstil.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enum som anger tillåten stil för talets textrepresentation |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>\& | En pekare till ett objekt som innehåller strängformatinformationen |

### Returvärde

Det osignerade 8-bitars heltalsvärdet som motsvarar talet som representeras av den angivna strängen

## Convert::ToSByte(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::CultureInfo>&) metod

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::NumberFormatInfo>&) metod

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String&, Globalization::NumberStyles, std::nullptr_t) metod

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) metod

```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr<Object>&, const SharedPtr<IFormatProvider>&) metod

Konverterar det angivna inneslutna värdet till motsvarande 8-bitars heltalsvärde.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)<[Object](../../object/)>\& | Den delade pekaren till objektet som innesluter värdet som ska konverteras |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>\& | Strängformatet som ska användas om den inneslutna värdestypen är [String](../../string/) |

### Returvärde

Ett 8-bitars heltalsvärde som motsvarar det angivna inneslutna värdet

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