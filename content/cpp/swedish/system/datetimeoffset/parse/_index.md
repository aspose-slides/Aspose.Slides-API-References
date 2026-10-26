---
title: Parse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen till DateTimeOffset-ekvivalent.
type: docs
weight: 703
url: /sv/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) metod

Konverterar den angivna strängen till [DateTimeOffset](../) motsvarande.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) att konvertera. |

### Returvärde

[DateTimeOffset](../) som är motsvarande **input**.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metod

Konverterar den angivna strängen till [DateTimeOffset](../)-objekt med den angivna formatleverantören och formateringsstilen.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) att konvertera. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatleverantör. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datum- och tidsformateringsstilar. |

### Returvärde

[DateTimeOffset](../) som är motsvarande **input**.

## Se även

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [DateTimeOffset](../)
* Klass [String](../../string/)
* Klass [IFormatProvider](../../iformatprovider/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)