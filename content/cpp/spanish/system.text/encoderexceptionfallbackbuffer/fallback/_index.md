---
title: Fallback()
second_title: Aspose.Slides para C++ Referencia de API
description: Maneja el error de codificación.
type: docs
weight: 27
url: /es/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) método

Maneja el error de codificación.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charUnknown | char_t | Caracteres desconocidos; ignorados. |
| index | int | Desplazamiento de caracteres desconocidos; ignorado. |

### Valor devuelto

Nunca devuelve realmente, lanza una excepción en su lugar.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) método

Maneja el error de codificación.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charUnknownHigh | char_t | Parte alta del par sustituto que provocó el error. |
| charUnknownLow | char_t | Parte baja del par sustituto que provocó el error. |
| index | int | Desplazamiento del carácter desconocido; ignorado. |

### Valor devuelto

Nunca devuelve realmente, lanza una excepción en su lugar.

## Ver también

* Clase [EncoderExceptionFallbackBuffer](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)