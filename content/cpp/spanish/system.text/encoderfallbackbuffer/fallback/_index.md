---
title: Fallback()
second_title: Referencia de API de Aspose.Slides para C++
description: Implementa el procedimiento de reserva real.
type: docs
weight: 14
url: /es/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) método

Implementa el procedimiento de reserva real.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charUnknown | char_t | El codificador de caracteres no puede codificar. |
| index | int | [Index](../../../system/index/) del carácter que provocó el error. |

### Valor de retorno

True si el búfer procesa los caracteres desconocidos, false si los ignora.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) método

Implementa el procedimiento de reserva real.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charUnknownHigh | char_t | Parte alta del par sustituto que provocó el error. |
| charUnknownLow | char_t | Parte baja del par sustituto que provocó el error. |
| index | int | [Index](../../../system/index/) del carácter que provocó el error. |

### Valor de retorno

True si el búfer procesa los caracteres desconocidos, false si los ignora.

## Ver también

* Clase [EncoderFallbackBuffer](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)