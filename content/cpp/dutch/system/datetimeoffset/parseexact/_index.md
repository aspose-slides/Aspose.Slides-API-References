---
title: ParseExact()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven string naar een DateTimeOffset object met behulp van het opgegeven formaat, de formatprovider en de opmaakstijl.
type: docs
weight: 716
url: /nl/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) methode


Converteert de opgegeven string naar een [DateTimeOffset](../) object met behulp van het opgegeven formaat, de formatprovider en de opmaakstijl.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) om te converteren. |
| format | const [String](../../string/)\& | Formaatstring. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datum- en tijdopmaakstijlen. |

### Retourwaarde

[DateTimeOffset](../) dat gelijk is aan de **input**.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) methode


Converteert de opgegeven string naar een [DateTimeOffset](../) object met behulp van de opgegeven formaten, de formatprovider en de opmaakstijl.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) om te converteren. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) van formaat-strings. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datum- en tijdopmaakstijlen. |

### Retourwaarde

[DateTimeOffset](../) dat gelijk is aan de **input**.

## Zie ook

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [DateTimeOffset](../)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)