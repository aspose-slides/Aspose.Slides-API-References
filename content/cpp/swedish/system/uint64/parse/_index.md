---
title: Parse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 64-bitars osignerade heltal.
type: docs
weight: 1
url: /sv/system/uint64/parse/
---
## UInt64::Parse(const String\&) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 64-bitars osignerade heltal.

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |

### Returvärde

Det 64-bitars osignerade heltalet som motsvarar numret som representeras av den angivna strängen.

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 64-bitars osignerade heltal med den angivna formateringsinformationen.

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller information om strängformatet. |

### Returvärde

Det 64-bitars osignerade heltalet som motsvarar numret som representeras av den angivna strängen.

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) metod




```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 64-bitars osignerade heltal med den angivna formateringsinformationen och talformatet.

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enumerationen som specificerar den tillåtna stilen för talets teckenrepresentation. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller information om strängformatet. |

### Returvärde

Det 64-bitars osignerade heltalet som motsvarar numret som representeras av den angivna strängen.

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metod




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Se också

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)