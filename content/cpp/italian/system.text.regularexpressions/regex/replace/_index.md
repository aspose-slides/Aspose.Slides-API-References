---
title: Replace()
second_title: Riferimento API di Aspose.Slides per C++
description: Sostituisce tutte le corrispondenze dell'espressione regolare nella stringa con la stringa di sostituzione.
type: docs
weight: 92
url: /it/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) metodo


Sostituisce tutte le corrispondenze dell'espressione regolare nella stringa con la stringa di sostituzione.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| replacement | const [String](../../../system/string/)\& | Stringa di sostituzione. |

### Valore di ritorno

Stringa di input con tutte le corrispondenze dell'espressione regolare sostituite con la stringa di sostituzione.

## Regex::Replace(const String\&, const char_t *) metodo


Sostituisce tutte le corrispondenze dell'espressione regolare nella stringa con la stringa di sostituzione.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| replacement | const char_t * | Stringa di sostituzione. |

### Valore di ritorno

Stringa di input con tutte le corrispondenze dell'espressione regolare sostituite con la stringa di sostituzione.

## Regex::Replace(const String\&, const MatchEvaluator\&) metodo


Sostituisce tutte le corrispondenze nella stringa con stringhe di sostituzione generate dal delegato.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegato per generare le stringhe di sostituzione in base alle corrispondenze. |

### Valore di ritorno

Stringhe di input con tutte le corrispondenze sostituite.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) metodo


Sostituisce tutte le corrispondenze nella stringa con stringhe di sostituzione generate dal delegato.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegato per generare le stringhe di sostituzione in base alle corrispondenze. |
| count | int | Numero massimo di sostituzioni. |

### Valore di ritorno

Stringhe di input con tutte le corrispondenze sostituite.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) metodo


Sostituisce tutte le corrispondenze nella stringa con stringhe di sostituzione generate dal delegato.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegato per generare le stringhe di sostituzione in base alle corrispondenze. |
| count | int | Numero massimo di sostituzioni. |
| startat | int | [Index](../../../system/index/) nella stringa di input dove iniziare la sostituzione. |

### Valore di ritorno

Stringhe di input con tutte le corrispondenze sostituite.

## Regex::Replace(const String\&, const String\&, int) metodo


Sostituisce sottostringhe nella stringa. Non implementato.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) metodo


Sostituisce sottostringhe nella stringa. Non implementato.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) metodo


Sostituisce tutte le corrispondenze dell'espressione regolare nella stringa con la stringa di sostituzione.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| pattern | const char_t * | [Regex](../) modello. |
| replacement | const char_t * | Stringa di sostituzione. |

### Valore di ritorno

Stringa di input con tutte le corrispondenze dell'espressione regolare sostituite con la stringa di sostituzione.

## Regex::Replace(const String\&, const String\&, const char_t *) metodo


Sostituisce tutte le corrispondenze dell'espressione regolare nella stringa con la stringa di sostituzione.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) modello. |
| replacement | const char_t * | Stringa di sostituzione. |

### Valore di ritorno

Stringa di input con tutte le corrispondenze dell'espressione regolare sostituite con la stringa di sostituzione.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) metodo


Sostituisce tutte le corrispondenze nella stringa con stringhe di sostituzione generate dal delegato (funzione statica).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) modello. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegato per generare le stringhe di sostituzione in base alle corrispondenze. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opzioni. |

### Valore di ritorno

Stringhe di input con tutte le corrispondenze sostituite.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) metodo


Sostituisce tutte le corrispondenze dell'espressione regolare nella stringa con la stringa di sostituzione.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) modello. |
| replacement | const [String](../../../system/string/)\& | Stringa di sostituzione. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opzioni. |

### Valore di ritorno

Stringa di input con tutte le corrispondenze dell'espressione regolare sostituite con la stringa di sostituzione.

## Regex::Replace(const String\&, const String\&, const String\&) metodo


Sostituisce le corrispondenze dell'espressione regolare.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| pattern | const [String](../../../system/string/)\& | Modello RegExp. |
| replacement | const [String](../../../system/string/)\& | Stringa di sostituzione. |

### Valore di ritorno

[String](../../../system/string/) con tutte le corrispondenze sostituite.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) metodo


Sostituisce le corrispondenze dell'espressione regolare.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| pattern | const [String](../../../system/string/)\& | Modello RegExp. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegato per generare la stringa di sostituzione per ogni corrispondenza. |

### Valore di ritorno

[String](../../../system/string/) con tutte le corrispondenze sostituite.

## Vedi anche

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)