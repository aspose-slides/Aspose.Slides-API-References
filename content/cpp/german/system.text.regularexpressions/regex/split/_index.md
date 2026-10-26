---
title: Split()
second_title: Aspose.Slides für C++ API-Referenz
description: Teilt Zeichenkette anhand von Regex-Übereinstimmungen.
type: docs
weight: 105
url: /de/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) Methode


Teilt Zeichenkette anhand von Regex-Übereinstimmungen.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) zum Teilen. |

### Rückgabewert

[Array](../../../system/array/) von Teilzeichenketten zwischen den Treffern.

## Regex::Split(const String\&, int) Methode


Teilt Zeichenkette anhand von Regex-Übereinstimmungen.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) zum Teilen. |
| count | int | Begrenzung der Anzahl von Teilzeichenketten. |

### Rückgabewert

[Array](../../../system/array/) von Teilzeichenketten zwischen den Treffern.

## Regex::Split(const String\&, int, int) Methode


Teilt eine Eingabezeichenkette eine festgelegte maximale Anzahl von Malen in ein Array von Teilzeichenketten, an den Positionen, die durch einen regulären Ausdruck im [Regex](../)-Konstruktor definiert sind. Die Suche nach dem regulären Ausdruck beginnt an einer angegebenen Zeichenposition in der Eingabezeichenkette.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Die Zeichenkette, die gespalten werden soll. |
| count | int | Die maximale Anzahl der Splits. |
| startat | int | Die Zeichenposition in der Eingabezeichenkette, an der die Suche beginnt. |

### Rückgabewert

Ein Array von Zeichenketten.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) Methode


Teilt Zeichenkette anhand von Regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| pattern | const [String](../../../system/string/)\& | Regexp-Muster. |
| options | [RegexOptions](../../regexoptions/) | Übereinstimmungsoptionen. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Zeitlimit. |

### Rückgabewert

[Array](../../../system/array/) von Zeichenketten zwischen den Treffern.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) Methode


Teilt Zeichenkette anhand von Regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| pattern | const [String](../../../system/string/)\& | Regexp-Muster. |
| count | int | [Match](../../match/) Zahlenlimit. |
| options | [RegexOptions](../../regexoptions/) | Übereinstimmungsoptionen. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Zeitlimit. |

### Rückgabewert

[Array](../../../system/array/) von Zeichenketten zwischen den Treffern.

## Siehe auch

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [Regex](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Namensraum [System::Text::RegularExpressions](../../)
* Bibliothek [Aspose.Slides](../../../)