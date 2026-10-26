---
title: Split()
second_title: Referência da API Aspose.Slides para C++
description: Divide a string por correspondências de regex.
type: docs
weight: 105
url: /pt/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) método


Divide a string por correspondências de regex.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) para dividir. |

### Valor de Retorno

[Array](../../../system/array/) de substrings entre correspondências.

## Regex::Split(const String\&, int) método


Divide a string por correspondências de regex.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) para dividir. |
| count | int | Limite do número de substrings. |

### Valor de Retorno

[Array](../../../system/array/) de substrings entre correspondências.

## Regex::Split(const String\&, int, int) método


Divide uma string de entrada um número máximo especificado de vezes em um array de substrings, nas posições definidas por uma expressão regular especificada no construtor [Regex](../). A busca pelo padrão da expressão regular começa em uma posição de caractere especificada na string de entrada.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | A string a ser dividida. |
| count | int | O número máximo de vezes que a divisão pode ocorrer. |
| startat | int | A posição de caractere na string de entrada onde a pesquisa começará. |

### Valor de Retorno

Um array de strings.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) método


Divide a string por regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| pattern | const [String](../../../system/string/)\& | Padrão regexp. |
| options | [RegexOptions](../../regexoptions/) | Opções de correspondência. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Tempo limite. |

### Valor de Retorno

[Array](../../../system/array/) de strings entre correspondências.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) método


Divide a string por regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| pattern | const [String](../../../system/string/)\& | Padrão regexp. |
| count | int | [Match](../../match/) limite de número. |
| options | [RegexOptions](../../regexoptions/) | Opções de correspondência. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Tempo limite. |

### Valor de Retorno

[Array](../../../system/array/) de strings entre correspondências.

## Veja Também

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)