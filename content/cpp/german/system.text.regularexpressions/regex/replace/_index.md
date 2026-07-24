---
title: Replace()
second_title: Aspose.Slides für C++ API-Referenz
description: Ersetzt alle Übereinstimmungen von regex in einer Zeichenkette durch die Ersetzungszeichenkette.
type: docs
weight: 92
url: /de/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) Methode


Ersetzt alle Übereinstimmungen von regex in der Zeichenkette durch die Ersetzungszeichenkette.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| replacement | const [String](../../../system/string/)\& | Ersetzungszeichenkette. |

### Rückgabewert

Eingabezeichenkette, in der alle regex-Übereinstimmungen durch die Ersetzungszeichenkette ersetzt wurden.

## Regex::Replace(const String\&, const char_t *) Methode


Ersetzt alle Übereinstimmungen von regex in der Zeichenkette durch die Ersetzungszeichenkette.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| replacement | const char_t * | Ersetzungszeichenkette. |

### Rückgabewert

Eingabezeichenkette, in der alle regex-Übereinstimmungen durch die Ersetzungszeichenkette ersetzt wurden.

## Regex::Replace(const String\&, const MatchEvaluator\&) Methode


Ersetzt alle Übereinstimmungen in der Zeichenkette durch von einem Delegaten erzeugte Ersetzungszeichenketten.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat zur Erzeugung von Ersetzungszeichenketten basierend auf Übereinstimmungen. |

### Rückgabewert

Eingabezeichenketten mit allen ersetzten Übereinstimmungen.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) Methode


Ersetzt alle Übereinstimmungen in der Zeichenkette durch von einem Delegaten erzeugte Ersetzungszeichenketten.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat zur Erzeugung von Ersetzungszeichenketten basierend auf Übereinstimmungen. |
| count | int | Begrenzung der Ersetzungsanzahl. |

### Rückgabewert

Eingabezeichenketten mit allen ersetzten Übereinstimmungen.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) Methode


Ersetzt alle Übereinstimmungen in der Zeichenkette durch von einem Delegaten erzeugte Ersetzungszeichenketten.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat zur Erzeugung von Ersetzungszeichenketten basierend auf Übereinstimmungen. |
| count | int | Begrenzung der Ersetzungsanzahl. |
| startat | int | [Index](../../../system/index/) in Eingabezeichenkette, ab der die Ersetzung beginnt. |

### Rückgabewert

Eingabezeichenketten mit allen ersetzten Übereinstimmungen.

## Regex::Replace(const String\&, const String\&, int) Methode


Ersetzt Teilzeichenketten in der Zeichenkette. Nicht implementiert.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) Methode


Ersetzt Teilzeichenketten in der Zeichenkette. Nicht implementiert.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) Methode


Ersetzt alle Übereinstimmungen von regex in der Zeichenkette durch die Ersetzungszeichenkette.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| pattern | const char_t * | [Regex](../) Muster. |
| replacement | const char_t * | Ersetzungszeichenkette. |

### Rückgabewert

Eingabezeichenkette, in der alle regex-Übereinstimmungen durch die Ersetzungszeichenkette ersetzt wurden.

## Regex::Replace(const String\&, const String\&, const char_t *) Methode


Ersetzt alle Übereinstimmungen von regex in der Zeichenkette durch die Ersetzungszeichenkette.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) Muster. |
| replacement | const char_t * | Ersetzungszeichenkette. |

### Rückgabewert

Eingabezeichenkette, in der alle regex-Übereinstimmungen durch die Ersetzungszeichenkette ersetzt wurden.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) Methode


Ersetzt alle Übereinstimmungen in der Zeichenkette durch von einem Delegaten erzeugte Ersetzungszeichenketten (statische Funktion).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) Muster. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat zur Erzeugung von Ersetzungszeichenketten basierend auf Übereinstimmungen. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) Optionen. |

### Rückgabewert

Eingabezeichenketten mit allen ersetzten Übereinstimmungen.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) Methode


Ersetzt alle Übereinstimmungen von regex in der Zeichenkette durch die Ersetzungszeichenkette.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) Muster. |
| replacement | const [String](../../../system/string/)\& | Ersetzungszeichenkette. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) Optionen. |

### Rückgabewert

Eingabezeichenkette, in der alle regex-Übereinstimmungen durch die Ersetzungszeichenkette ersetzt wurden.

## Regex::Replace(const String\&, const String\&, const String\&) Methode


Ersetzt regex-Übereinstimmungen.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| pattern | const [String](../../../system/string/)\& | Regexp-Muster. |
| replacement | const [String](../../../system/string/)\& | Ersetzungszeichenkette. |

### Rückgabewert

[String](../../../system/string/) mit allen Übereinstimmungen ersetzt.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) Methode


Ersetzt regex-Übereinstimmungen.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Eingabezeichenkette. |
| pattern | const [String](../../../system/string/)\& | Regexp-Muster. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat zur Erzeugung einer Ersetzungszeichenkette für jede Übereinstimmung. |

### Rückgabewert

[String](../../../system/string/) mit allen Übereinstimmungen ersetzt.

## Siehe auch

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)