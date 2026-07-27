---
title: GetNumericValue()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o valor numérico associado ao caractere especificado.
type: docs
weight: 27
url: /pt/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) método

Obtém o valor numérico associado ao caractere especificado.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ch | char16_t | Caractere Unicode. |

### Valor de retorno

O valor numérico ou -1 se o caractere especificado não for um caractere numérico.

## CharUnicodeInfo::GetNumericValue(const String\&, int) método

Obtém o valor numérico associado ao caractere no índice especificado da string.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | A string contendo o caractere Unicode. |
| index | int | O índice do caractere Unicode. |

### Valor de retorno

O valor numérico ou -1 se o caractere especificado não for um caractere numérico.

## Ver também

* Classe [CharUnicodeInfo](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::Globalization](../../)
* Library [Aspose.Slides](../../../)