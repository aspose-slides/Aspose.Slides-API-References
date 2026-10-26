---
title: GetByteCount()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene la cantidad de bytes necesarios para codificar un búfer.
type: docs
weight: 40
url: /es/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) método

Obtiene la cantidad de bytes necesarios para codificar un búfer.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |
| index | int | [Buffer](../../../system/buffer/) desplazamiento. |
| count | int | Número de caracteres a codificar. |
| flush | **bool** | Si es true, limpia el estado interno del codificador después del cálculo. |

### Valor devuelto

Número de bytes requeridos para codificar el búfer.

## ICUEncoder::GetByteCount(const char_t *, int, bool) método

Obtiene la cantidad de bytes necesarios para codificar un búfer.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| count | int | Número de caracteres a codificar. |
| flush | **bool** | Si es true, limpia el estado interno del codificador después del cálculo. |

### Valor devuelto

Número de bytes requeridos para codificar el búfer.

## Ver también

* Definición de tipo [ArrayPtr](../../../system/arrayptr/)
* Clase [ICUEncoder](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)