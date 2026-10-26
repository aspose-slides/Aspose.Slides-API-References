---
title: ToSingle()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte cuatro bytes del arreglo especificado que comienza en el índice especificado a un valor de punto flotante de precisión simple.
type: docs
weight: 131
url: /es/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) method

Convierte cuatro bytes del arreglo especificado comenzando en el índice especificado a un valor de punto flotante de precisión simple.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el arreglo donde comenzar a tomar bytes para la conversión |

### Valor devuelto

Valor de punto flotante de precisión simple resultante de la conversión

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) method

Convierte cuatro bytes del arreglo especificado comenzando en el índice especificado a un valor de punto flotante de precisión simple.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el arreglo donde comenzar a tomar bytes para la conversión |

### Valor devuelto

Valor de punto flotante de precisión simple resultante de la conversión

## Véase también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [BitConverter](../)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)