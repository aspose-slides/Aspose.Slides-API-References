---
title: DateTimeStyles
second_title: Aspose.Slides para C++ Referência da API
description: Define opções de formatação de data e hora. Flags de bits.
type: docs
weight: 456
url: /pt/system.globalization/datetimestyles/
---
## DateTimeStyles enum

Define opções de formatação de data e hora. Flags de bits.

```cpp
enum class DateTimeStyles : int32_t
```

### Valores

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Padrão. |
| AllowLeadingWhite | 1 | Ignora espaços em branco iniciais. |
| AllowTrailingWhite | 2 | Ignora espaços em branco finais. |
| AllowInnerWhite | 4 | Ignora espaços em branco internos. |
| AllowWhiteSpaces | n/a | Ignora todos os espaços em branco. |
| NoCurrentDateDefault | 8 | Ao analisar uma string de data/hora, se todos os componentes ano/mês/dia estiverem ausentes, define a data padrão como 0001/1/1, em vez do ano/mês/dia atual. |
| AdjustToUniversal | 16 | Ao analisar uma string de data/hora, se houver um especificador de fuso horário (\"GMT\",\"Z\",\"+xxxx\",\"-xxxx\"), ajustaremos o horário analisado com base no GMT. |
| AssumeLocal | 32 | Se nenhum fuso horário for informado, use o fuso horário local. |
| AssumeUniversal | 64 | Se nenhum fuso horário for informado, use UTC. |
| RoundtripKind | 128 | Tenta preservar se a entrada é não especificada, local ou UTC. |

## Veja Também

* Espaço de nomes [System::Globalization](../)
* Biblioteca [Aspose.Slides](../../)