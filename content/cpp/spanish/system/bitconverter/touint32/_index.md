---
title: ToUInt32()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte cuatro bytes del array especificado a partir del índice especificado a un valor entero sin signo de 32 bits.
type: docs
weight: 105
url: /es/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) método

Convierte cuatro bytes del array especificado a partir del índice especificado a un valor entero sin signo de 32 bits.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el array donde comenzar a tomar los bytes para la conversión |

### Valor de retorno

Valor entero sin signo de 32 bits resultante de la conversión

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) método

Convierte cuatro bytes del array especificado a partir del índice especificado a un valor entero sin signo de 32 bits.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el array donde comenzar a tomar los bytes para la conversión |

### Valor de retorno

Valor entero sin signo de 32 bits resultante de la conversión

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [BitConverter](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)