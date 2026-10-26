---
title: TryParseExact()
second_title: Aspose.Slides voor C++ API-referentie
description: Probeert de opgegeven string om te zetten naar een DateTimeOffset-object met behulp van de opgegeven formaten, formatprovider en opmaakstijl.
type: docs
weight: 742
url: /nl/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method

Probeert de opgegeven string om te zetten naar een [DateTimeOffset](../) object met behulp van de opgegeven formaten, opmaakprovider en opmaakstijl.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) om te converteren. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Arrays van opmaakstrings. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Opmaakprovider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datum- en tijdopmaakstijlen. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) die gelijk is aan de **input**. |

### Retourwaarde

true als de **input** succesvol is geconverteerd, anders - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method

Probeert de opgegeven string om te zetten naar een [DateTimeOffset](../) object met behulp van de opgegeven indeling, opmaakprovider en opmaakstijl.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) om te converteren. |
| format | const [String](../../string/)\& | Opmaakstring. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Opmaakprovider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datum- en tijdopmaakstijlen. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) die gelijk is aan de **input**. |

### Retourwaarde

true als de **input** succesvol is geconverteerd, anders - false.

## Zie ook

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [DateTimeOffset](../)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)