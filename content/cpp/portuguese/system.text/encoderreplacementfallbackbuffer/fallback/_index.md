---
title: Fallback()
second_title: Aspose.Slides para C++ Referência da API
description: Lida com falha de codificação.
type: docs
weight: 27
url: /pt/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) método


Lida com falha de codificação.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| charUnknown | char_t | Caractere desconhecido; ignorado. |
| index | int | Posição do caractere desconhecido; ignorado. |

### Valor de Retorno

True se a string de substituição for fornecida e não estiver vazia, false caso contrário.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) método


Lida com falha de codificação.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| charUnknownHigh | char_t | Parte alta do par substituto que gerou o erro. |
| charUnknownLow | char_t | Parte baixa do par substituto que gerou o erro. |
| index | int | Posição do caractere desconhecido; ignorado. |

### Valor de Retorno

True se a string de substituição for fornecida e não estiver vazia, false caso contrário.

## Veja Também

* Classe [EncoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)