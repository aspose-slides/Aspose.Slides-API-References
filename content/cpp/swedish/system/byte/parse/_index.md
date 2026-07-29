---
title: Parse()
second_title: Aspose.Slides för C++ API-referens
description: Omvandlar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 8-bitars osignerade heltal.
type: docs
weight: 1
url: /sv/system/byte/parse/
---
## Byte::Parse(const String\&) metod

Omvandlar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 8-bitars osignerade heltal.

```cpp
static uint8_t System::Byte::Parse(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska omvandlas. |

### Returvärde

Det 8-bitars osignerade heltalet som är lika med talet som representeras av den angivna strängen.

## Byte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metod

Omvandlar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 8-bitars osignerade heltal med den medföljande formateringsinformationen.

```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska omvandlas. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller information om strängformatet. |

### Returvärde

Det 8-bitars osignerade heltalet som är lika med talet som representeras av den angivna strängen.

## Byte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, std::nullptr_t) metod




```cpp
static uint8_t System::Byte::Parse(const String &value, std::nullptr_t)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod

Omvandlar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 8-bitars osignerade heltal med den medföljande formateringsinformationen och talstilen.

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska omvandlas. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enumen som specificerar den tillåtna stilen för talets teckenrepresentation. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller information om strängformatet. |

### Returvärde

Det 8-bitars osignerade heltalet som är lika med talet som representeras av den angivna strängen.

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metod




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* klass [String](../../string/)
* klass [Byte](../)
* klass [IFormatProvider](../../iformatprovider/)
* klass [CultureInfo](../../../system.globalization/cultureinfo/)
* klass [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* namnrymd [System](../../)
* Library [Aspose.Slides](../../../)