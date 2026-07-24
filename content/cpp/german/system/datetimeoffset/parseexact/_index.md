---
title: ParseExact()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenfolge in ein DateTimeOffset-Objekt unter Verwendung des angegebenen Formats, des Format-Providers und des Formatierungsstils.
type: docs
weight: 716
url: /de/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) Methode

Konvertiert die angegebene Zeichenfolge in ein [DateTimeOffset](../)-Objekt unter Verwendung des angegebenen Formats, des Format-Providers und des Formatierungsstils.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) zum Konvertieren. |
| format | const [String](../../string/)\& | Formatzeichenfolge. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format-Provider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datums- und Zeitformatierungsstile. |

### Rückgabewert

[DateTimeOffset](../), das dem **input** entspricht.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) Methode

Konvertiert die angegebene Zeichenfolge in ein [DateTimeOffset](../)-Objekt unter Verwendung der angegebenen Formate, des Format-Providers und des Formatierungsstils.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) zum Konvertieren. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) von Formatzeichenfolgen. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format-Provider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datums- und Zeitformatierungsstile. |

### Rückgabewert

[DateTimeOffset](../), das dem **input** entspricht.

## Siehe Auch

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)