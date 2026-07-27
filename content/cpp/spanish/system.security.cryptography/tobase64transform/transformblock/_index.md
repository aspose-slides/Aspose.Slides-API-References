---
title: TransformBlock()
second_title: Referencia de API de Aspose.Slides para C++
description: Procesa un bloque de datos y copia los datos al arreglo de salida.
type: docs
weight: 53
url: /es/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) método

Procesa un bloque de datos y copia los datos al arreglo de salida.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para leer datos de. |
| inputOffset | **int32_t** | Desplazamiento del búfer de entrada. |
| inputCount | **int32_t** | Número de bytes a procesar. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Búfer de salida donde copiar los datos; nullptr para no copiar. |
| outputOffset | **int32_t** | Desplazamiento del búfer de salida. |

### Valor devuelto

Número de bytes escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ToBase64Transform](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)