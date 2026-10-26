---
title: Parse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven string naar een DateTimeOffset-equivalent.
type: docs
weight: 703
url: /nl/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) methode


Converteert de opgegeven string naar een [DateTimeOffset](../) equivalent.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) om te converteren. |

### Retourwaarde

[DateTimeOffset](../) die gelijk is aan de **input**.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) methode


Converteert de opgegeven string naar een [DateTimeOffset](../) object met behulp van de opgegeven opmaakprovider en opmaakstijl.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) om te converteren. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Opmaakprovider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datum- en tijdopmaakstijlen. |

### Retourwaarde

[DateTimeOffset](../) die gelijk is aan de **input**.

## Zie ook

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [DateTimeOffset](../)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)