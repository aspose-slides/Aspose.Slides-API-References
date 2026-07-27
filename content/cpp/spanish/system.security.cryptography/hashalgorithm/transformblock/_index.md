---
title: TransformBlock()
second_title: Referencia de API de Aspose.Slides para C++
description: Procesa un bloque de datos y copia los datos al array de salida.
type: docs
weight: 66
url: /es/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


Procesa un bloque de datos y copia los datos al array de salida.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para leer datos de. |
| inputOffset | int | Desplazamiento del buffer de entrada. |
| inputCount | int | Número de bytes a procesar. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer de salida para copiar datos; nullptr para no copiar. |
| outputOffset | int | Desplazamiento del buffer de salida. |

### Valor de retorno

Número de bytes escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [HashAlgorithm](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)