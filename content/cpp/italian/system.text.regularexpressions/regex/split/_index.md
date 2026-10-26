---
title: Split()
second_title: Riferimento API di Aspose.Slides per C++
description: Divide la stringa in base alle corrispondenze regex.
type: docs
weight: 105
url: /it/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) metodo

Dividi la stringa in base alle corrispondenze regex.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) da dividere. |

### Valore di ritorno

[Array](../../../system/array/) di sottostringhe tra le corrispondenze.

## Regex::Split(const String\&, int) metodo

Dividi la stringa in base alle corrispondenze regex.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) da dividere. |
| count | int | Numero limite di sottostringhe. |

### Valore di ritorno

[Array](../../../system/array/) di sottostringhe tra le corrispondenze.

## Regex::Split(const String\&, int, int) metodo

Divide una stringa di input un numero massimo specificato di volte in un array di sottostringhe, nelle posizioni definite da un'espressione regolare specificata nel costruttore [Regex](../). La ricerca del modello di espressione regolare inizia in una posizione di carattere specificata nella stringa di input.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | La stringa da dividere. |
| count | int | Il numero massimo di volte in cui la divisione può avvenire. |
| startat | int | La posizione del carattere nella stringa di input a partire dalla quale inizia la ricerca. |

### Valore di ritorno

Un array di stringhe.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) metodo

Dividi la stringa per regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| pattern | const [String](../../../system/string/)\& | Pattern regexp. |
| options | [RegexOptions](../../regexoptions/) | Opzioni di corrispondenza. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |

### Valore di ritorno

[Array](../../../system/array/) di stringhe tra le corrispondenze.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) metodo

Dividi la stringa per regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| pattern | const [String](../../../system/string/)\& | Pattern regexp. |
| count | int | [Match](../../match/) limite numerico. |
| options | [RegexOptions](../../regexoptions/) | Opzioni di corrispondenza. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |

### Valore di ritorno

[Array](../../../system/array/) di stringhe tra le corrispondenze.

## Vedi anche

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)