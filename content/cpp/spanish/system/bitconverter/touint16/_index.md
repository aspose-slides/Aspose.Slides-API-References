---
title: ToUInt16()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte dos bytes del arreglo especificado comenzando en el índice especificado a un valor entero sin signo de 16 bits.
type: docs
weight: 92
url: /es/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) method

Convierte dos bytes del arreglo especificado comenzando en el índice especificado a un valor entero sin signo de 16 bits.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el arreglo en el que comenzar a tomar los bytes para la conversión |

### Valor de retorno

Valor entero sin signo de 16 bits resultante de la conversión

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) method

Convierte dos bytes del arreglo especificado comenzando en el índice especificado a un valor entero sin signo de 16 bits.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el arreglo en el que comenzar a tomar los bytes para la conversión |

### Valor de retorno

Valor entero sin signo de 16 bits resultante de la conversión

## Véase también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [BitConverter](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)