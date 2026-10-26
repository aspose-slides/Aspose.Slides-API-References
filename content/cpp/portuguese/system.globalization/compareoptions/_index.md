---
title: CompareOptions
second_title: Aspose.Slides para C++ Referência da API
description: Opções de comparação de strings.
type: docs
weight: 430
url: /pt/system.globalization/compareoptions/
---
## CompareOptions enum

[String](../../system/string/) opções de comparação.

```cpp
enum class CompareOptions : int32_t
```

### Valores

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Nenhuma opção especial. |
| IgnoreCase | 1 | Ignorar maiúsculas/minúsculas. |
| IgnoreNonSpace | 2 | Ignorar caracteres combinados não espaçadores, por exemplo diacríticos. |
| IgnoreSymbols | 4 | Incluir espaços em branco, sinais de pontuação e assim por diante. |
| IgnoreKanaType | 8 | Ignorar tipo kana (japonês). |
| IgnoreWidth | 16 | Ignorar largura de caracteres ao comparar cadeias. |
| OrdinalIgnoreCase | 268435456 | Comparação ordinal com diferença de maiúsculas/minúsculas ignorada. |
| StringSort | 536870912 | Usar algoritmo de ordenação de strings para comparar caracteres. |
| Ordinal | 1073741824 | Comparar códigos UTF diretamente para a primeira comparação. |

## Ver Também

* Namespace [System::Globalization](../)
* Biblioteca [Aspose.Slides](../../)