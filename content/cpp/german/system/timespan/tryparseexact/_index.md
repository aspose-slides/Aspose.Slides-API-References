---
title: TryParseExact()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die Zeichenkette in ein entsprechendes TimeSpan-Objekt unter Verwendung der angegebenen Formate und des Formatproviders und gibt das Ergebnis der Konvertierung zurück.
type: docs
weight: 573
url: /de/system/timespan/tryparseexact/
---
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method


Konvertiert die Zeichenkette in ein entsprechendes [TimeSpan](../) Objekt unter Verwendung der angegebenen Formate und des Formatproviders und gibt das Ergebnis der Konvertierung zurück.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | Eingabezeichenkette. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) von Formatzeichenketten. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider, der kulturspezifische Formatinformationen bereitstellt. |
| result | [TimeSpan](../)\& | Zeitintervall, das der Zeichenkette entspricht. |

### Rückgabewert

Wahr, wenn die Zeichenkette erfolgreich konvertiert wurde; andernfalls falsch.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method


Konvertiert die Zeichenkette in ein entsprechendes [TimeSpan](../) Objekt unter Verwendung des angegebenen Formats, des Formatproviders und der Stile und gibt das Ergebnis der Konvertierung zurück.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | Eingabezeichenkette. |
| format | const [String](../../string/)\& | Standard- oder benutzerdefinierte Formatzeichenkette. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider, der kulturspezifische Formatinformationen bereitstellt. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Definiert Elemente, die in der Eingabezeichenkette vorhanden sein können. |
| result | [TimeSpan](../)\& | Zeitintervall, das der Zeichenkette entspricht. |

### Rückgabewert

Wahr, wenn die Zeichenkette erfolgreich konvertiert wurde; andernfalls falsch.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method


Konvertiert die Zeichenkette in ein entsprechendes [TimeSpan](../) Objekt unter Verwendung der angegebenen Formate, des Formatproviders und der Stile und gibt das Ergebnis der Konvertierung zurück.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | Eingabezeichenkette. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) von Formatzeichenketten. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider, der kulturspezifische Formatinformationen bereitstellt. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Definiert Elemente, die in der Eingabezeichenkette vorhanden sein können. |
| result | [TimeSpan](../)\& | Zeitintervall, das der Zeichenkette entspricht. |

### Rückgabewert

Wahr, wenn die Zeichenkette erfolgreich konvertiert wurde; andernfalls falsch.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method


Konvertiert die Zeichenkette in ein entsprechendes [TimeSpan](../) Objekt unter Verwendung des angegebenen Formats und des Formatproviders und gibt das Ergebnis der Konvertierung zurück.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | Eingabezeichenkette. |
| format | const [String](../../string/)\& | Standard- oder benutzerdefinierte Formatzeichenkette. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider, der kulturspezifische Formatinformationen bereitstellt. |
| result | [TimeSpan](../)\& | Zeitintervall, das der Zeichenkette entspricht. |

### Rückgabewert

Wahr, wenn die Zeichenkette erfolgreich konvertiert wurde; andernfalls falsch.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, TimeSpan &result)
```

## Siehe auch

* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [TimeSpan](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)