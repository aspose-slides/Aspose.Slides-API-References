---
title: Fallback()
second_title: Referencia de API de Aspose.Slides para C++
description: Implementa el procedimiento real de fallback.
type: docs
weight: 14
url: /es/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) método


Implementa el procedimiento de retroceso real.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) de bytes que incluye el que el decodificador no puede decodificar. |
| index | int | [Index](../../../system/index/) del byte que desencadenó el error. |

### Valor devuelto

True if buffer processes unknown bytes, false if it ignores them.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [DecoderFallbackBuffer](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)