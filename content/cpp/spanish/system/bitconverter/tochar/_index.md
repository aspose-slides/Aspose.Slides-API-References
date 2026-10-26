---
title: ToChar()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte dos bytes del array especificado a partir del índice especificado en un valor char_t.
type: docs
weight: 40
url: /es/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) método

Convierte dos bytes del array especificado a partir del índice especificado en un valor char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el array en el que comenzar a tomar bytes para la conversión |

### Valor devuelto

char_t value resultante de la conversión

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) método

Convierte dos bytes del array especificado a partir del índice especificado en un valor char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el array en el que comenzar a tomar bytes para la conversión |

### Valor devuelto

char_t value resultante de la conversión

## Véase también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [BitConverter](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)