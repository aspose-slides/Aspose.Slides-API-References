---
title: TryParse()
second_title: Aspose.Slides voor C++ API-referentie
description: Probeert de opgegeven tekenreeks om te zetten naar een DateTimeOffset object.
type: docs
weight: 729
url: /nl/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) methode

Probeert de opgegeven tekenreeks om te zetten naar een [DateTimeOffset](../) object.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) om te converteren. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) dat gelijk is aan de **input**. |

### Retourwaarde

true als de **input** succesvol geconverteerd is, anders - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) methode

Probeert de opgegeven tekenreeks om te zetten naar een [DateTimeOffset](../) object met behulp van de opgegeven formaatprovider en opmaakstijl.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) om te converteren. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formaatprovider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datum- en tijdopmaakstijlen. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) dat gelijk is aan de **input**. |

### Retourwaarde

true als de **input** succesvol geconverteerd is, anders - false.

## Zie ook

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)