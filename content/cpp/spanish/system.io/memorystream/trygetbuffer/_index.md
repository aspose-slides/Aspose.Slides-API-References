---
title: TryGetBuffer()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la matriz de bytes sin signo con la que se creó este flujo.
type: docs
weight: 170
url: /es/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) método


Devuelve la matriz de bytes sin signo de la que se creó este flujo.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | matriz de bytes - parámetro de salida. Cuando este método devuelve true, el segmento de la matriz de bytes del que se creó este flujo; cuando este método devuelve false, este parámetro se establece en el valor predeterminado. |

### Valor de retorno

True si la conversión tuvo éxito.

## Véase también

* Clase [ArraySegment](../../../system/arraysegment/)
* Clase [MemoryStream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)