---
title: Parse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenfolge in das DateTimeOffset-Äquivalent.
type: docs
weight: 703
url: /de/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) Methode


Konvertiert die angegebene Zeichenfolge in das Äquivalent von [DateTimeOffset](../).

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) zum Konvertieren. |

### Rückgabewert

[DateTimeOffset](../) das dem **input** entspricht.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) Methode


Konvertiert die angegebene Zeichenfolge in ein [DateTimeOffset](../)-Objekt unter Verwendung des angegebenen Formatproviders und des Formatierungsstils.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) zum Konvertieren. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datums- und Zeitformatierungsstile. |

### Rückgabewert

[DateTimeOffset](../) das dem **input** entspricht.

## Siehe auch

* Aufzählung [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [DateTimeOffset](../)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)