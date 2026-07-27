---
title: ToBoolean()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte un byte del array especificado a partir del índice especificado en un valor booleano.
type: docs
weight: 27
url: /es/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) method


Convierte un byte del array especificado a partir del índice especificado en un valor booleano.

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el array en el que comenzar a extraer bytes para la conversión |

### Valor devuelto

[Boolean](../../boolean/) valor resultante de la conversión

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) method


Convierte un byte del array especificado a partir del índice especificado en un valor booleano.

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el array en el que comenzar a extraer bytes para la conversión |

### Valor devuelto

[Boolean](../../boolean/) valor resultante de la conversión

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [BitConverter](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)