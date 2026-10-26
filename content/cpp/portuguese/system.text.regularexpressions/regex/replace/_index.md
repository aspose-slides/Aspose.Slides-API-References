---
title: Replace()
second_title: Referência da API Aspose.Slides para C++
description: Substitui todas as correspondências de regex na string por string de substituição.
type: docs
weight: 92
url: /pt/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) método

Substitui todas as correspondências de regex na string pelo string de substituição.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| replacement | const [String](../../../system/string/)\& | String de substituição. |

### Valor de Retorno

String de entrada com todas as correspondências de regex substituídas pelo string de substituição.

## Regex::Replace(const String\&, const char_t *) método

Substitui todas as correspondências de regex na string pelo string de substituição.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| replacement | const char_t * | String de substituição. |

### Valor de Retorno

String de entrada com todas as correspondências de regex substituídas pelo string de substituição.

## Regex::Replace(const String\&, const MatchEvaluator\&) método

Substitui todas as correspondências na string por strings de substituição geradas por delegação.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegado para gerar strings de substituição com base nas correspondências. |

### Valor de Retorno

Strings de entrada com todas as correspondências substituídas.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) método

Substitui todas as correspondências na string por strings de substituição geradas por delegação.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegado para gerar strings de substituição com base nas correspondências. |
| count | int | Limite de número de substituições. |

### Valor de Retorno

Strings de entrada com todas as correspondências substituídas.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) método

Substitui todas as correspondências na string por strings de substituição geradas por delegação.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegado para gerar strings de substituição com base nas correspondências. |
| count | int | Limite de número de substituições. |
| startat | int | [Index](../../../system/index/) na string de entrada onde iniciar a substituição. |

### Valor de Retorno

Strings de entrada com todas as correspondências substituídas.

## Regex::Replace(const String\&, const String\&, int) método

Substitui substrings na string. Não implementado.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) método

Substitui substrings na string. Não implementado.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) método

Substitui todas as correspondências de regex na string pelo string de substituição.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| pattern | const char_t * | [Regex](../) padrão. |
| replacement | const char_t * | String de substituição. |

### Valor de Retorno

String de entrada com todas as correspondências de regex substituídas pelo string de substituição.

## Regex::Replace(const String\&, const String\&, const char_t *) método

Substitui todas as correspondências de regex na string pelo string de substituição.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) padrão. |
| replacement | const char_t * | String de substituição. |

### Valor de Retorno

String de entrada com todas as correspondências de regex substituídas pelo string de substituição.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) método

Substitui todas as correspondências na string por strings de substituição geradas por delegação (função estática).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) padrão. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegado para gerar strings de substituição com base nas correspondências. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opções. |

### Valor de Retorno

Strings de entrada com todas as correspondências substituídas.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) método

Substitui todas as correspondências de regex na string pelo string de substituição.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) padrão. |
| replacement | const [String](../../../system/string/)\& | String de substituição. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opções. |

### Valor de Retorno

String de entrada com todas as correspondências de regex substituídas pelo string de substituição.

## Regex::Replace(const String\&, const String\&, const String\&) método

Substitui correspondências de regex.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| pattern | const [String](../../../system/string/)\& | Padrão Regexp. |
| replacement | const [String](../../../system/string/)\& | String de substituição. |

### Valor de Retorno

[String](../../../system/string/) com todas as correspondências substituídas.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) método

Substitui correspondências de regex.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| pattern | const [String](../../../system/string/)\& | Padrão Regexp. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegado para gerar string de substituição para cada correspondência. |

### Valor de Retorno

[String](../../../system/string/) com todas as correspondências substituídas.

## Veja Também

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)