---
title: Replace()
second_title: Aspose.Slides för C++ API-referens
description: Ersätter alla matchningar av regex i strängen med ersättningssträngen.
type: docs
weight: 92
url: /sv/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) metod

Ersätter alla matchningar av regex i strängen med ersättningssträngen.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| replacement | const [String](../../../system/string/)\& | Ersättningssträng. |

### Returvärde

Indatasträng med alla regex-matchningar ersatta med ersättningssträngen.

## Regex::Replace(const String\&, const char_t *) metod

Ersätter alla matchningar av regex i strängen med ersättningssträngen.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| replacement | const char_t * | Ersättningssträng. |

### Returvärde

Indatasträng med alla regex-matchningar ersatta med ersättningssträngen.

## Regex::Replace(const String\&, const MatchEvaluator\&) metod

Ersätter alla matchningar i strängen med delegat-genererade ersättningssträngar.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat för att generera ersättningssträngar baserat på matchningar. |

### Returvärde

Indatasträngar med alla matchningar ersatta.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) metod

Ersätter alla matchningar i strängen med delegat-genererade ersättningssträngar.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat för att generera ersättningssträngar baserat på matchningar. |
| count | int | Gräns för antal ersättningar. |

### Returvärde

Indatasträngar med alla matchningar ersatta.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) metod

Ersätter alla matchningar i strängen med delegat-genererade ersättningssträngar.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat för att generera ersättningssträngar baserat på matchningar. |
| count | int | Gräns för antal ersättningar. |
| startat | int | [Index](../../../system/index/) i indatasträngen för att börja ersättningen vid. |

### Returvärde

Indatasträngar med alla matchningar ersatta.

## Regex::Replace(const String\&, const String\&, int) metod

Ersätter delsträngar i strängen. Ej implementerad.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) metod

Ersätter delsträngar i strängen. Ej implementerad.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) metod

Ersätter alla matchningar av regex i strängen med ersättningssträngen.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| pattern | const char_t * | [Regex](../) mönster. |
| replacement | const char_t * | Ersättningssträng. |

### Returvärde

Indatasträng med alla regex-matchningar ersatta med ersättningssträngen.

## Regex::Replace(const String\&, const String\&, const char_t *) metod

Ersätter alla matchningar av regex i strängen med ersättningssträngen.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) mönster. |
| replacement | const char_t * | Ersättningssträng. |

### Returvärde

Indatasträng med alla regex-matchningar ersatta med ersättningssträngen.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) metod

Ersätter alla matchningar i strängen med delegat-genererade ersättningssträngar (statisk funktion).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) mönster. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat för att generera ersättningssträngar baserat på matchningar. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) alternativ. |

### Returvärde

Indatasträngar med alla matchningar ersatta.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) metod

Ersätter alla matchningar av regex i strängen med ersättningssträngen.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) mönster. |
| replacement | const [String](../../../system/string/)\& | Ersättningssträng. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) alternativ. |

### Returvärde

Indatasträng med alla regex-matchningar ersatta med ersättningssträngen.

## Regex::Replace(const String\&, const String\&, const String\&) metod

Ersätter regex-matchningar.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| pattern | const [String](../../../system/string/)\& | Regexp-mönster. |
| replacement | const [String](../../../system/string/)\& | Ersättningssträng. |

### Returvärde

[String](../../../system/string/) med alla matchningar ersatta.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) metod

Ersätter regex-matchningar.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| pattern | const [String](../../../system/string/)\& | Regexp-mönster. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat för att generera ersättningssträng för varje matchning. |

### Returvärde

[String](../../../system/string/) med alla matchningar ersatta.

## Se även

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* klass [String](../../../system/string/)
* klass [Regex](../)
* namnrymd [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)