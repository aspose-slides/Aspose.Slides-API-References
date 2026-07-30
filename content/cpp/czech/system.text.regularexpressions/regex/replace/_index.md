---
title: Replace()
second_title: Aspose.Slides pro C++ - reference API
description: Nahrazuje všechny shody regulárního výrazu v řetězci řetězcem nahrazení.
type: docs
weight: 92
url: /cs/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) metoda

Nahrazuje všechny shody regulárního výrazu v řetězci řetězcem nahrazení.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| replacement | const [String](../../../system/string/)\& | Řetězec nahrazení. |

### Návratová hodnota

Vstupní řetězec se všemi shodami regulárního výrazu nahrazenými řetězcem nahrazení.

## Regex::Replace(const String\&, const char_t *) metoda

Nahrazuje všechny shody regulárního výrazu v řetězci řetězcem nahrazení.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| replacement | const char_t * | Řetězec nahrazení. |

### Návratová hodnota

Vstupní řetězec se všemi shodami regulárního výrazu nahrazenými řetězcem nahrazení.

## Regex::Replace(const String\&, const MatchEvaluator\&) metoda

Nahrazuje všechny shody v řetězci řetězciami generovanými delegátem.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegát pro generování řetězců nahrazení na základě shod. |

### Návratová hodnota

Vstupní řetězce se všemi shodami nahrazenými.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) metoda

Nahrazuje všechny shody v řetězci řetězciami generovanými delegátem.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegát pro generování řetězců nahrazení na základě shod. |
| count | int | Limit počtu nahrazení. |

### Návratová hodnota

Vstupní řetězce se všemi shodami nahrazenými.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) metoda

Nahrazuje všechny shody v řetězci řetězciami generovanými delegátem.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegát pro generování řetězců nahrazení na základě shod. |
| count | int | Limit počtu nahrazení. |
| startat | int | [Index](../../../system/index/) ve vstupním řetězci, kde zahájit nahrazování. |

### Návratová hodnota

Vstupní řetězce se všemi shodami nahrazenými.

## Regex::Replace(const String\&, const String\&, int) metoda

Nahrazuje podřetězce v řetězci. Není implementováno.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) metoda

Nahrazuje podřetězce v řetězci. Není implementováno.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) metoda

Nahrazuje všechny shody regulárního výrazu v řetězci řetězcem nahrazení.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| pattern | const char_t * | [Regex](../) vzor. |
| replacement | const char_t * | Řetězec nahrazení. |

### Návratová hodnota

Vstupní řetězec se všemi shodami regulárního výrazu nahrazenými řetězcem nahrazení.

## Regex::Replace(const String\&, const String\&, const char_t *) metoda

Nahrazuje všechny shody regulárního výrazu v řetězci řetězcem nahrazení.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) vzor. |
| replacement | const char_t * | Řetězec nahrazení. |

### Návratová hodnota

Vstupní řetězec se všemi shodami regulárního výrazu nahrazenými řetězcem nahrazení.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) metoda

Nahrazuje všechny shody v řetězci řetězciemi generovanými delegátem (statická funkce).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) vzor. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegát pro generování řetězců nahrazení na základě shod. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) možnosti. |

### Návratová hodnota

Vstupní řetězce se všemi shodami nahrazenými.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) metoda

Nahrazuje všechny shody regulárního výrazu v řetězci řetězcem nahrazení.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) vzor. |
| replacement | const [String](../../../system/string/)\& | Řetězec nahrazení. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) možnosti. |

### Návratová hodnota

Vstupní řetězec se všemi shodami regulárního výrazu nahrazenými řetězcem nahrazení.

## Regex::Replace(const String\&, const String\&, const String\&) metoda

Nahrazuje shody regulárního výrazu.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| pattern | const [String](../../../system/string/)\& | Regexp vzor. |
| replacement | const [String](../../../system/string/)\& | Řetězec nahrazení. |

### Návratová hodnota

[String](../../../system/string/) se všemi shodami nahrazenými.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) metoda

Nahrazuje shody regulárního výrazu.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| pattern | const [String](../../../system/string/)\& | Regexp vzor. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegát pro generování řetězce nahrazení pro každou shodu. |

### Návratová hodnota

[String](../../../system/string/) se všemi shodami nahrazenými.

## Viz také

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)