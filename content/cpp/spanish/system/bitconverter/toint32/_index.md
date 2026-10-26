---
title: ToInt32()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte cuatro bytes del arreglo especificado a partir del índice especificado a un valor entero de 32 bits.
type: docs
weight: 66
url: /es/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) método


Convierte cuatro bytes del arreglo especificado a partir del índice especificado a un valor entero de 32 bits.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el arreglo en el que comenzar a tomar bytes para la conversión |

### Valor de retorno

Valor entero de 32 bits resultante de la conversión

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) método


Convierte cuatro bytes del arreglo especificado a partir del índice especificado a un valor entero de 32 bits.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el arreglo en el que comenzar a tomar bytes para la conversión |

### Valor de retorno

Valor entero de 32 bits resultante de la conversión

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [BitConverter](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)