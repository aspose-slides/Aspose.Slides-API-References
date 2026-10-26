---
title: Replace()
second_title: Aspose.Slides voor C++ API-referentie
description: Vervangt alle regex overeenkomsten in de string door de vervangingsstring.
type: docs
weight: 92
url: /nl/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) method


Vervangt alle regex-overeenkomsten in de string door de vervangingsstring.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| replacement | const [String](../../../system/string/)\& | Vervangingsstring. |

### Retourwaarde

Invoertekenreeks met alle regex-overeenkomsten vervangen door de vervangingsstring.

## Regex::Replace(const String\&, const char_t *) method


Vervangt alle regex-overeenkomsten in de string door de vervangingsstring.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| replacement | const char_t * | Vervangingsstring. |

### Retourwaarde

Invoertekenreeks met alle regex-overeenkomsten vervangen door de vervangingsstring.

## Regex::Replace(const String\&, const MatchEvaluator\&) method


Vervangt alle overeenkomsten in de string door door delegate-gegenereerde vervangingsstrings.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate om vervangingsstrings te genereren op basis van overeenkomsten. |

### Retourwaarde

Invoertekenreeksen met alle overeenkomsten vervangen.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) method


Vervangt alle overeenkomsten in de string door door delegate-gegenereerde vervangingsstrings.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate om vervangingsstrings te genereren op basis van overeenkomsten. |
| count | int | Limiet voor het aantal vervangingen. |

### Retourwaarde

Invoertekenreeksen met alle overeenkomsten vervangen.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) method


Vervangt alle overeenkomsten in de string door door delegate-gegenereerde vervangingsstrings.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate om vervangingsstrings te genereren op basis van overeenkomsten. |
| count | int | Limiet voor het aantal vervangingen. |
| startat | int | [Index](../../../system/index/) in invoertekenreeks om vervanging te starten bij. |

### Retourwaarde

Invoertekenreeksen met alle overeenkomsten vervangen.

## Regex::Replace(const String\&, const String\&, int) method


Vervangt sub-strings in de string. Niet geïmplementeerd.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) method


Vervangt sub-strings in de string. Niet geïmplementeerd.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) method


Vervangt alle regex-overeenkomsten in de string door de vervangingsstring.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| pattern | const char_t * | [Regex](../) patroon. |
| replacement | const char_t * | Vervangingsstring. |

### Retourwaarde

Invoertekenreeks met alle regex-overeenkomsten vervangen door de vervangingsstring.

## Regex::Replace(const String\&, const String\&, const char_t *) method


Vervangt alle regex-overeenkomsten in de string door de vervangingsstring.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) patroon. |
| replacement | const char_t * | Vervangingsstring. |

### Retourwaarde

Invoertekenreeks met alle regex-overeenkomsten vervangen door de vervangingsstring.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) method


Vervangt alle overeenkomsten in de string door door delegate-gegenereerde vervangingsstrings (statische functie).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) patroon. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate om vervangingsstrings te genereren op basis van overeenkomsten. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opties. |

### Retourwaarde

Invoertekenreeksen met alle overeenkomsten vervangen.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) method


Vervangt alle regex-overeenkomsten in de string door de vervangingsstring.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) patroon. |
| replacement | const [String](../../../system/string/)\& | Vervangingsstring. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opties. |

### Retourwaarde

Invoertekenreeks met alle regex-overeenkomsten vervangen door de vervangingsstring.

## Regex::Replace(const String\&, const String\&, const String\&) method


Vervangt regex-overeenkomsten.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| pattern | const [String](../../../system/string/)\& | Regexp-patroon. |
| replacement | const [String](../../../system/string/)\& | Vervangingsstring. |

### Retourwaarde

[String](../../../system/string/) met alle overeenkomsten vervangen.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) method


Vervangt regex-overeenkomsten.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| pattern | const [String](../../../system/string/)\& | Regexp-patroon. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate om een vervangingsstring te genereren voor elke overeenkomst. |

### Retourwaarde

[String](../../../system/string/) met alle overeenkomsten vervangen.

## Zie ook

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)