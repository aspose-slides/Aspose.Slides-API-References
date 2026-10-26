---
title: ToInt16()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte dos bytes del array especificado comenzando en el índice especificado a un valor entero de 16 bits.
type: docs
weight: 53
url: /es/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) método


Convierte dos bytes del array especificado comenzando en el índice especificado a un valor entero de 16 bits.

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el array en el que comenzar a tomar bytes para la conversión |

### Valor de retorno

Valor entero de 16 bits resultante de la conversión

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) método


Convierte dos bytes del array especificado comenzando en el índice especificado a un valor entero de 16 bits.

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el array en el que comenzar a tomar bytes para la conversión |

### Valor de retorno

Valor entero de 16 bits resultante de la conversión

## Véase también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [BitConverter](../)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)