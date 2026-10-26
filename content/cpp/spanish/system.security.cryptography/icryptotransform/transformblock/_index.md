---
title: TransformBlock()
second_title: Aspose.Slides para la referencia de API de C++
description: Procesa un bloque de datos y copia los datos al arreglo de salida.
type: docs
weight: 1
url: /es/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) método

Procesa un bloque de datos y copia los datos al arreglo de salida.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para leer datos de. |
| inputOffset | int | Desplazamiento del búfer de entrada. |
| inputCount | int | Número de bytes a procesar. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Búfer de salida donde copiar los datos; nullptr para no copiar. |
| outputOffset | int | Desplazamiento del búfer de salida. |

### Valor de retorno

Número de bytes escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ICryptoTransform](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Librería [Aspose.Slides](../../../)