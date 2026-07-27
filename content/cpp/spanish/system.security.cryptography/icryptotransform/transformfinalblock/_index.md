---
title: TransformFinalBlock()
second_title: Referencia de API de Aspose.Slides para C++
description: Procesa el último bloque de datos y calcula el valor de salida.
type: docs
weight: 14
url: /es/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) method


Procesa el último bloque de datos y calcula el valor de salida.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para leer datos de. |
| inputOffset | int | Desplazamiento del búfer de entrada. |
| inputCount | int | Número de bytes a procesar. |

### Valor devuelto

Salida calculada para toda la secuencia de entrada.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ICryptoTransform](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)