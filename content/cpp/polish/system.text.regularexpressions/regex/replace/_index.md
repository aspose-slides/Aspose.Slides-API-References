---
title: Replace()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zastępuje wszystkie dopasowania wyrażenia regularnego w łańcuchu znaków ciągiem zamiennym.
type: docs
weight: 92
url: /pl/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) metoda


Zastępuje wszystkie dopasowania wyrażenia regularnego w łańcuchu znaków ciągiem zamiennym.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Łańcuch wejściowy. |
| replacement | const [String](../../../system/string/)\& | Łańcuch zamienny. |

### Wartość zwracana

Łańcuch wejściowy ze wszystkimi dopasowaniami wyrażenia regularnego zastąpionymi ciągiem zamiennym.

## Regex::Replace(const String\&, const char_t *) metoda


Zastępuje wszystkie dopasowania wyrażenia regularnego w łańcuchu znaków ciągiem zamiennym.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Łańcuch wejściowy. |
| replacement | const char_t * | Łańcuch zamienny. |

### Wartość zwracana

Łańcuch wejściowy ze wszystkimi dopasowaniami wyrażenia regularnego zastąpionymi ciągiem zamiennym.

## Regex::Replace(const String\&, const MatchEvaluator\&) metoda


Zastępuje wszystkie dopasowania w łańcuchu znaków ciągami generowanymi przez delegata.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Łańcuch wejściowy. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat generujący ciągi zamienne na podstawie dopasowań. |

### Wartość zwracana

Łańcuchy wejściowe ze wszystkimi dopasowaniami zastąpionymi.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) metoda


Zastępuje wszystkie dopasowania w łańcuchu znaków ciągami generowanymi przez delegata.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Łańcuch wejściowy. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat generujący ciągi zamienne na podstawie dopasowań. |
| count | int | Limit liczby zamian. |

### Wartość zwracana

Łańcuchy wejściowe ze wszystkimi dopasowaniami zastąpionymi.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) metoda


Zastępuje wszystkie dopasowania w łańcuchu znaków ciągami generowanymi przez delegata.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Łańcuch wejściowy. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat generujący ciągi zamienne na podstawie dopasowań. |
| count | int | Limit liczby zamian. |
| startat | int | [Index](../../../system/index/) w łańcuchu wejściowym, od którego rozpocząć zamianę. |

### Wartość zwracana

Łańcuchy wejściowe ze wszystkimi dopasowaniami zastąpionymi.

## Regex::Replace(const String\&, const String\&, int) metoda


Zastępuje podłańcuchy w łańcuchu znaków. Nie zaimplementowano.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) metoda


Zastępuje podłańcuchy w łańcuchu znaków. Nie zaimplementowano.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) metoda


Zastępuje wszystkie dopasowania wyrażenia regularnego w łańcuchu znaków ciągiem zamiennym.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Łańcuch wejściowy. |
| pattern | const char_t * | [Regex](../) wzorzec. |
| replacement | const char_t * | Łańcuch zamienny. |

### Wartość zwracana

Łańcuch wejściowy ze wszystkimi dopasowaniami wyrażenia regularnego zastąpionymi ciągiem zamiennym.

## Regex::Replace(const String\&, const String\&, const char_t *) metoda


Zastępuje wszystkie dopasowania wyrażenia regularnego w łańcuchu znaków ciągiem zamiennym.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Łańcuch wejściowy. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) wzorzec. |
| replacement | const char_t * | Łańcuch zamienny. |

### Wartość zwracana

Łańcuch wejściowy ze wszystkimi dopasowaniami wyrażenia regularnego zastąpionymi ciągiem zamiennym.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) metoda


Zastępuje wszystkie dopasowania w łańcuchu znaków ciągami generowanymi przez delegata (funkcja statyczna).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Łańcuch wejściowy. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) wzorzec. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat generujący ciągi zamienne na podstawie dopasowań. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opcje. |

### Wartość zwracana

Łańcuchy wejściowe ze wszystkimi dopasowaniami zastąpionymi.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) metoda


Zastępuje wszystkie dopasowania wyrażenia regularnego w łańcuchu znaków ciągiem zamiennym.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Łańcuch wejściowy. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) wzorzec. |
| replacement | const [String](../../../system/string/)\& | Łańcuch zamienny. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opcje. |

### Wartość zwracana

Łańcuch wejściowy ze wszystkimi dopasowaniami wyrażenia regularnego zastąpionymi ciągiem zamiennym.

## Regex::Replace(const String\&, const String\&, const String\&) metoda


Zastępuje dopasowania wyrażenia regularnego.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Łańcuch wejściowy. |
| pattern | const [String](../../../system/string/)\& | Wzorzec wyrażenia regularnego. |
| replacement | const [String](../../../system/string/)\& | Łańcuch zamienny. |

### Wartość zwracana

[String](../../../system/string/) ze wszystkimi dopasowaniami zastąpionymi.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) metoda


Zastępuje dopasowania wyrażenia regularnego.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Łańcuch wejściowy. |
| pattern | const [String](../../../system/string/)\& | Wzorzec wyrażenia regularnego. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegat generujący ciąg zamienny dla każdego dopasowania. |

### Wartość zwracana

[String](../../../system/string/) ze wszystkimi dopasowaniami zastąpionymi.

## Zobacz także

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)