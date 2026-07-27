---
title: ToUInt64()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte ocho bytes del arreglo especificado a partir del índice especificado a un valor entero sin signo de 64 bits.
type: docs
weight: 118
url: /es/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) método


Convierte ocho bytes del arreglo especificado a partir del índice especificado a un valor entero sin signo de 64 bits.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el arreglo en el que comenzar a tomar los bytes para la conversión |

### Valor devuelto

Valor entero sin signo de 64 bits resultante de la conversión

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) método


Convierte ocho bytes del arreglo especificado a partir del índice especificado a un valor entero sin signo de 64 bits.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el arreglo en el que comenzar a tomar los bytes para la conversión |

### Valor devuelto

Valor entero sin signo de 64 bits resultante de la conversión

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [BitConverter](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)