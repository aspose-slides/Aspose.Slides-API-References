---
title: TryParseExact()
second_title: Aspose.Slides för C++ API-referens
description: Försöker konvertera den angivna strängen till ett DateTimeOffset-objekt med de angivna formaten, formatleverantören och formateringsstilen.
type: docs
weight: 742
url: /sv/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) metod

Försöker konvertera den angivna strängen till [DateTimeOffset](../)-objekt med de angivna formaten, formatleverantören och formateringsstilen.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) att konvertera. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Arrayer av formatsträngar. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatleverantör. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datum- och tidsformateringsstilar. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) som är motsvarande **input**. |

### Returvärde

true om **input** konverterades framgångsrikt, annars - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) metod

Försöker konvertera den angivna strängen till [DateTimeOffset](../)-objekt med det angivna formatet, formatleverantören och formateringsstilen.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) att konvertera. |
| format | const [String](../../string/)\& | Formatsträng. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatleverantör. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datum- och tidsformateringsstilar. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) som är motsvarande **input**. |

### Returvärde

true om **input** konverterades framgångsrikt, annars - false.

## Se även

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)