---
title: TryParseExact()
second_title: Aspose.Slides für C++ API-Referenz
description: Versucht, die angegebene Zeichenkette in ein DateTimeOffset-Objekt zu konvertieren, wobei die angegebenen Formate, der Formatprovider und der Formatstil verwendet werden.
type: docs
weight: 742
url: /de/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) Methode


Versucht, die angegebene Zeichenkette in ein [DateTimeOffset](../)-Objekt zu konvertieren, wobei die angegebenen Formate, der Formatprovider und der Formatstil verwendet werden.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) zu konvertieren. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Arrays von Formatzeichenketten. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datums- und Zeitformatierungsstile. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../), das dem **input** entspricht. |

### Rückgabewert

true, wenn die **input** erfolgreich konvertiert wurde, andernfalls - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) Methode


Versucht, die angegebene Zeichenkette in ein [DateTimeOffset](../)-Objekt zu konvertieren, wobei das angegebene Format, der Formatprovider und der Formatstil verwendet werden.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) zu konvertieren. |
| format | const [String](../../string/)\& | Formatzeichenkette. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Datums- und Zeitformatierungsstile. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../), das dem **input** entspricht. |

### Rückgabewert

true, wenn die **input** erfolgreich konvertiert wurde, andernfalls - false.

## Siehe auch

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)