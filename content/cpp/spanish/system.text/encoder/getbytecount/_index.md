---
title: GetByteCount()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el número de bytes necesarios para codificar un búfer.
type: docs
weight: 40
url: /es/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) método


Obtiene el número de bytes necesarios para codificar un búfer.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |
| index | int | [Buffer](../../../system/buffer/) desplazamiento. |
| count | int | Número de caracteres a codificar. |
| flush | **bool** | Si es verdadero, limpia el estado interno del codificador después del cálculo. |

### Valor devuelto

Número de bytes requeridos para codificar el búfer.

## Encoder::GetByteCount(const char_t *, int, bool) método


Obtiene el número de bytes necesarios para codificar un búfer.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| count | int | Número de caracteres a codificar. |
| flush | **bool** | Si es verdadero, limpia el estado interno del codificador después del cálculo. |

### Valor devuelto

Número de bytes requeridos para codificar el búfer.

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Encoder](../)
* Espacio de nombres [System::Text](../../)
* Library [Aspose.Slides](../../../)