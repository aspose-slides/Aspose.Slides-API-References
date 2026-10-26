---
title: Fallback()
second_title: Referência da API Aspose.Slides para C++
description: Manipula falha de codificação.
type: docs
weight: 27
url: /pt/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) método


Manipula falha de codificação.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| charUnknown | char_t | Caracteres desconhecidos; ignorado. |
| index | int | Deslocamento de caracteres desconhecidos; ignorado. |

### Valor de Retorno

Nunca retorna realmente, lança uma exceção em vez disso.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) método


Manipula falha de codificação.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| charUnknownHigh | char_t | Parte alta do par substituto que provocou o erro. |
| charUnknownLow | char_t | Parte baixa do par substituto que provocou o erro. |
| index | int | Deslocamento de caractere desconhecido; ignorado. |

### Valor de Retorno

Nunca retorna realmente, lança uma exceção em vez disso.

## Veja Também

* Classe [EncoderExceptionFallbackBuffer](../)
* Namespace [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)