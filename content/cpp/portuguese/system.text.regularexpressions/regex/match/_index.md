---
title: Match()
second_title: Referência da API Aspose.Slides para C++
description: Correspondência de regex contra a string.
type: docs
weight: 66
url: /pt/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) método


Correspondência de regex contra a string.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String alvo. |

### Valor de Retorno

[Match](../../match/) valor contendo o status da correspondência e subcorrespondências.

## Regex::Match(const String\&, int, int) método


Correspondência de regex contra a string.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String alvo. |
| startat | int | Índice inicial. |
| length | int | Número de caracteres a percorrer (0 para percorrer a string inteira). |

### Valor de Retorno

[Match](../../match/) valor contendo o status da correspondência e subcorrespondências.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) método


Correspondência de string e padrão.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| pattern | const [String](../../../system/string/)\& | Padrão RegExp. |
| options | [RegexOptions](../../regexoptions/) | Opções de correspondência. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Tempo limite. |
| startat | int | [Match](../../match/) posição inicial. |
| length | int | Número de caracteres a percorrer (0 desabilita limite). |

### Valor de Retorno

Primeira correspondência encontrada.

## Veja Também

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Classe [String](../../../system/string/)
* Classe [Regex](../)
* Classe [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)