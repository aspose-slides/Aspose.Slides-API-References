---
title: Fallback()
second_title: Referência da API Aspose.Slides para C++
description: Implementa o procedimento real de fallback.
type: docs
weight: 14
url: /pt/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) método


Implementa o procedimento real de fallback.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| charUnknown | char_t | Codificador de caracteres falha ao codificar. |
| index | int | [Index](../../../system/index/) do caractere que gerou o erro. |

### Valor de Retorno

True se o buffer processa caracteres desconhecidos, false se os ignora.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) método


Implementa o procedimento real de fallback.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| charUnknownHigh | char_t | Parte alta do par substituto que gerou o erro. |
| charUnknownLow | char_t | Parte baixa do par substituto que gerou o erro. |
| index | int | [Index](../../../system/index/) do caractere que gerou o erro. |

### Valor de Retorno

True se o buffer processa caracteres desconhecidos, false se os ignora.

## Ver Também

* Classe [EncoderFallbackBuffer](../)
* Espaço de nomes [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)