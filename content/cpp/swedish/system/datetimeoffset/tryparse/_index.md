---
title: TryParse()
second_title: Aspose.Slides för C++ API-referens
description: Försöker konvertera den angivna strängen till DateTimeOffset-objekt.
type: docs
weight: 729
url: /sv/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) metod

Försöker konvertera den angivna strängen till [DateTimeOffset](../)-objekt.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) att konvertera. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) som är ekvivalent med **input**. |

### Returvärde

true if the **input** converted successfully, otherwise - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) metod

Försöker konvertera den angivna strängen till [DateTimeOffset](../)-objekt med den angivna formatleverantören och formateringsstilen.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) att konvertera. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatleverantör. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datum- och tidsformatstilar. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) som är ekvivalent med **input**. |

### Returvärde

true if the **input** converted successfully, otherwise - false.

## Se även

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [DateTimeOffset](../)
* Klass [IFormatProvider](../../iformatprovider/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)