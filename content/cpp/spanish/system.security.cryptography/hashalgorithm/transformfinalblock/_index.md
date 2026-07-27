---
title: TransformFinalBlock()
second_title: Referencia de API de Aspose.Slides para C++
description: Procesa el último bloque de datos y calcula el hash.
type: docs
weight: 79
url: /es/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) método


Procesa el último bloque de datos y calcula el hash.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para leer datos de. |
| inputOffset | int | Desplazamiento del búfer de entrada. |
| inputCount | int | Número de bytes a procesar. |

### Valor devuelto

Hash calculado para la secuencia completa de datos.

## Ver también

* Definición de tipo [ArrayPtr](../../../system/arrayptr/)
* Clase [HashAlgorithm](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)