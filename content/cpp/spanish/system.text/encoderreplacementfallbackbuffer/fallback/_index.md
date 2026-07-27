---
title: Fallback()
second_title: Referencia de API de Aspose.Slides para C++
description: Gestiona la falla de codificación.
type: docs
weight: 27
url: /es/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) método


Gestiona la falla de codificación.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charUnknown | char_t | Carácter desconocido; ignorado. |
| index | int | Posición del carácter desconocido; ignorada. |

### Valor devuelto

True si la cadena de reemplazo está provista y no está vacía, false en caso contrario.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) método


Gestiona la falla de codificación.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charUnknownHigh | char_t | Parte alta del par sustituto que provocó el error. |
| charUnknownLow | char_t | Parte baja del par sustituto que provocó el error. |
| index | int | Posición del carácter desconocido; ignorada. |

### Valor devuelto

True si la cadena de reemplazo está provista y no está vacía, false en caso contrario.

## Ver también

* Clase [EncoderReplacementFallbackBuffer](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)