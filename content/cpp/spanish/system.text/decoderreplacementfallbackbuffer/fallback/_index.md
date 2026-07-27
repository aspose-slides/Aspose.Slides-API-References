---
title: Fallback()
second_title: Referencia de API de Aspose.Slides para C++
description: Maneja el fallo de decodificación.
type: docs
weight: 27
url: /es/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) método

Maneja el fallo de decodificación.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) de bytes desconocidos; ignorado. |
| index | int | Desplazamiento de bytes desconocidos; ignorado. |

### Valor devuelto

True si se proporciona una cadena de reemplazo y no está vacía, false en caso contrario.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [DecoderReplacementFallbackBuffer](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)