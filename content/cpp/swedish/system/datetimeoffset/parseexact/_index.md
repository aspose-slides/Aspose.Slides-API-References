---
title: ParseExact()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen till DateTimeOffset-objekt med hjälp av det angivna formatet, formatleverantören och formateringsstilen.
type: docs
weight: 716
url: /sv/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metod

Konverterar den angivna strängen till [DateTimeOffset](../)-objekt med hjälp av det angivna formatet, formatleverantören och formateringsstilen.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) att konvertera. |
| format | const [String](../../string/)\& | Formatsträng. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatleverantör. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datum- och tidsformateringsstilar. |

### Returvärde

[DateTimeOffset](../) som är ekvivalent med **input**.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metod

Konverterar den angivna strängen till [DateTimeOffset](../)-objekt med hjälp av de angivna formaten, formatleverantören och formateringsstilen.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) att konvertera. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) av formatsträngar. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatleverantör. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datum- och tidsformateringsstilar. |

### Returvärde

[DateTimeOffset](../) som är ekvivalent med **input**.

## Se även

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)