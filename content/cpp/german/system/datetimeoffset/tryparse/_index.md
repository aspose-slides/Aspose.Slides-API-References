---
title: TryParse()
second_title: Aspose.Slides für C++ API-Referenz
description: Versucht, die angegebene Zeichenfolge in ein DateTimeOffset-Objekt zu konvertieren.
type: docs
weight: 729
url: /de/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) Methode

Versucht, die angegebene Zeichenfolge in ein [DateTimeOffset](../) Objekt zu konvertieren.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) zum Konvertieren. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../), das dem **input** entspricht. |

### Return Value

true, wenn **input** erfolgreich konvertiert wurde, andernfalls false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) Methode

Versucht, die angegebene Zeichenfolge unter Verwendung des angegebenen Formatproviders und des Formatstils in ein [DateTimeOffset](../) Objekt zu konvertieren.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) zum Konvertieren. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datums- und Zeitformatierungsstile. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../), das dem **input** entspricht. |

### Return Value

true, wenn **input** erfolgreich konvertiert wurde, andernfalls false.

## See Also

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)