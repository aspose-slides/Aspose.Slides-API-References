---
title: Matches()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém todas as correspondências da expressão regular na string fornecida ao corresponder repetidamente.
type: docs
weight: 79
url: /pt/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) método

Obtém todas as correspondências da expressão regular na string fornecida ao corresponder repetidamente.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| startat | int | [Index](../../../system/index/) para iniciar a correspondência em. |

### Valor de Retorno

Coleção de todas as correspondências encontradas.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) método

Obtém todas as correspondências entre a string e o padrão.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| pattern | const [String](../../../system/string/)\& | Padrão de expressão regular. |
| options | [RegexOptions](../../regexoptions/) | Opções de correspondência. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Tempo limite. |
| startat | int | [Match](../../match/) posição inicial. |
| length | int | Número de caracteres a percorrer (0 desativa o limite). |

### Valor de Retorno

Todas as correspondências encontradas ao corresponder repetidamente.

## Veja Também

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)