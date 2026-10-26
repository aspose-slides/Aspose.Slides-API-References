---
title: Match()
second_title: Aspose.Slides für C++ API Referenz
description: Vergleicht den regulären Ausdruck mit dem String.
type: docs
weight: 66
url: /de/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) Methode

Vergleicht den regulären Ausdruck mit dem String.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Zielzeichenfolge. |

### Rückgabewert

[Match](../../match/) Wert, der den Trefferstatus und Teilübereinstimmungen enthält.

## Regex::Match(const String\&, int, int) Methode

Vergleicht den regulären Ausdruck mit dem String.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Zielzeichenfolge. |
| startat | int | Anfangsindex. |
| length | int | Anzahl der zu durchsuchenden Zeichen (0, um den gesamten String zu durchsuchen). |

### Rückgabewert

[Match](../../match/) Wert, der den Trefferstatus und Teilübereinstimmungen enthält.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) Methode

Vergleicht den String und das Muster.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenfolge. |
| pattern | const [String](../../../system/string/)\& | Regexp-Muster. |
| options | [RegexOptions](../../regexoptions/) | Übereinstimmungsoptionen. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Zeitüberschreitung. |
| startat | int | [Match](../../match/) Anfangsposition. |
| length | int | Anzahl der zu durchsuchenden Zeichen (0 deaktiviert das Limit). |

### Rückgabewert

Erster gefundener Treffer.

## Siehe auch

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Klasse [String](../../../system/string/)
* Klasse [Regex](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Namensraum [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)