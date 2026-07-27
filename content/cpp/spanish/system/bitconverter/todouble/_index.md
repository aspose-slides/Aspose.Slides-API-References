---
title: ToDouble()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte ocho bytes del array especificado a partir del índice especificado a un valor de punto flotante de doble precisión.
type: docs
weight: 144
url: /es/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) method

Convierte ocho bytes del array especificado a partir del índice especificado a un valor de punto flotante de doble precisión.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en la matriz donde comenzar a tomar bytes para la conversión |

### Valor devuelto

Valor de punto flotante de doble precisión resultante de la conversión

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) method

Convierte ocho bytes del array especificado a partir del índice especificado a un valor de punto flotante de doble precisión.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en la matriz donde comenzar a tomar bytes para la conversión |

### Valor devuelto

Valor de punto flotante de doble precisión resultante de la conversión

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [BitConverter](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)