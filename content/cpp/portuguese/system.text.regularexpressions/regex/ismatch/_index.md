---
title: IsMatch()
second_title: Referência da API Aspose.Slides para C++
description: Correspondência de regex contra string.
type: docs
weight: 53
url: /pt/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) método

Correspondência de regex contra string.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String alvo. |
| startat | int | Índice inicial. |

### Valor de Retorno

Verdadeiro se a string corresponder à expressão regular, falso caso contrário.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) método

Verifica se a string corresponde ao padrão.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String de entrada. |
| pattern | const [String](../../../system/string/)\& | Padrão da expressão regular. |
| options | [RegexOptions](../../regexoptions/) | Opções de correspondência. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Tempo limite. |
| startat | int | [Match](../../match/) posição inicial. |

### Valor de Retorno

Verdadeiro se a correspondência for encontrada, falso caso contrário.

## Veja Também

* Enum [RegexOptions](../../regexoptions/)
* classe [String](../../../system/string/)
* classe [Regex](../)
* classe [TimeSpan](../../../system/timespan/)
* namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)