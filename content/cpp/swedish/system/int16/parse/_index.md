---
title: Parse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande 16-bitars signerade heltal.
type: docs
weight: 1
url: /sv/system/int16/parse/
---
## Int16::Parse(const String\&) metod


Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande 16-bitars signerade heltal.

```cpp
static int16_t System::Int16::Parse(const String &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras. |

### Returvärde

Det 16-bitars signerade heltalet som är lika med talet som representeras av den angivna strängen.

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande 16-bitars signerade heltal med hjälp av den angivna formateringsinformationen.

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formateringsinformationen för strängen. |

### Returvärde

Det 16-bitars signerade heltalet som är lika med talet som representeras av den angivna strängen.

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) metod




```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande 16-bitars signerade heltal med hjälp av den angivna formateringsinformationen och talstilen.

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enumerationen som specificerar den tillåtna stilen för talets strängrepresentation. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formateringsinformationen för strängen. |

### Returvärde

Det 16-bitars signerade heltalet som är lika med talet som representeras av den angivna strängen.

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metod 




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int16](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)