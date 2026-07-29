---
title: Parse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande 64-bitars heltal med tecken.
type: docs
weight: 1
url: /sv/system/int64/parse/
---
## Int64::Parse(const String\&) metod

Konverterar den angivna strängen som innehåller ett tal till motsvarande 64-bitars heltal med tecken.

```cpp
static int64_t System::Int64::Parse(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |

### Returvärde

Den 64-bitars heltal med tecken som är lika med talet som representeras av den angivna strängen.

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller ett tal till motsvarande 64-bitars heltal med tecken med den angivna formatinformationen.

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formatinformationen för strängen. |

### Returvärde

Den 64-bitars heltal med tecken som är lika med talet som representeras av den angivna strängen.

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) metod

```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller ett tal till motsvarande 64-bitars heltal med tecken med den angivna formatinformationen och talstil.

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-uppräkningen som anger den tillåtna stilen för talets strängrepresentation. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formatinformationen för strängen. |

### Returvärde

Den 64-bitars heltal med tecken som är lika med talet som representeras av den angivna strängen.

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metod

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [Int64](../)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)