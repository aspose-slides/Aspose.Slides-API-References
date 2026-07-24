---
title: IsMatch()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht einen regulären Ausdruck mit einer Zeichenkette.
type: docs
weight: 53
url: /de/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) method

Vergleicht einen regulären Ausdruck mit einer Zeichenkette.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Zielzeichenkette. |
| startat | int | Startindex. |

### Rückgabewert

Wahr, wenn die Zeichenkette mit dem regulären Ausdruck übereinstimmt, sonst falsch.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) method

Prüft, ob die Zeichenkette mit dem Muster übereinstimmt.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| pattern | const [String](../../../system/string/)\& | Regexp-Muster. |
| options | [RegexOptions](../../regexoptions/) | Übereinstimmungsoptionen. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Zeitüberschreitung. |
| startat | int | [Match](../../match/) Anfangsposition. |

### Rückgabewert

Wahr, wenn eine Übereinstimmung gefunden wurde, sonst falsch.

## Siehe auch

* Enum [RegexOptions](../../regexoptions/)
* Klasse [String](../../../system/string/)
* Klasse [Regex](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Namensraum [System::Text::RegularExpressions](../../)
* Bibliothek [Aspose.Slides](../../../)