---
title: Matches()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt alle Übereinstimmungen des regulären Ausdrucks in der angegebenen Zeichenkette durch wiederholtes Abgleichen.
type: docs
weight: 79
url: /de/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) Methode

Ermittelt alle Übereinstimmungen des regulären Ausdrucks in der angegebenen Zeichenkette durch wiederholtes Abgleichen.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| startat | int | [Index](../../../system/index/) Startposition für das Matching. |

### Rückgabewert

Sammlung aller gefundener Übereinstimmungen.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) Methode

Ermittelt alle Übereinstimmungen zwischen Zeichenkette und Muster.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| pattern | const [String](../../../system/string/)\& | Regexp-Muster. |
| options | [RegexOptions](../../regexoptions/) | Abgleichoptionen. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Zeitüberschreitung. |
| startat | int | [Match](../../match/) Anfangsposition. |
| length | int | Anzahl der zu durchsuchenden Zeichen (0 deaktiviert das Limit). |

### Rückgabewert

Alle gefundenen Übereinstimmungen durch wiederholtes Abgleichen.

## Siehe auch

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Klasse [String](../../../system/string/)
* Klasse [Regex](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Namensraum [System::Text::RegularExpressions](../../)
* Bibliothek [Aspose.Slides](../../../)