---
title: ToInt64()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte ocho bytes del array especificado a partir del índice especificado a un valor entero de 64 bits.
type: docs
weight: 79
url: /es/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) método

Convierte ocho bytes del array especificado comenzando en el índice especificado a un valor entero de 64 bits.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contiene bytes para convertir |
| startIndex | int | [Index](../../index/) en el array donde se deben comenzar a tomar bytes para la conversión |

### Valor de retorno

valor entero de 64 bits resultante de la conversión

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) método

Convierte ocho bytes del array especificado comenzando en el índice especificado a un valor entero de 64 bits.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contiene bytes para convertir |
| startIndex | int | [Index](../../index/) en el array donde se deben comenzar a tomar bytes para la conversión |

### Valor de retorno

valor entero de 64 bits resultante de la conversión

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [BitConverter](../)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)