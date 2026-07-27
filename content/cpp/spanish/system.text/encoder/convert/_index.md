---
title: Convert()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte caracteres a bytes.
type: docs
weight: 79
url: /es/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) método

Convierte caracteres a bytes.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |
| charIndex | int | Desplazamiento del búfer de entrada. |
| charCount | int | Tamaño del búfer de entrada. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Búfer de bytes de destino. |
| byteIndex | int | Desplazamiento del arreglo de destino. |
| byteCount | int | Tamaño del arreglo de destino. |
| flush | **bool** | Si es true, limpia el estado interno del codificador después del cálculo. |
| charsUsed | int\& | Referencia a la variable para almacenar el recuento de caracteres leídos. |
| bytesUsed | int\& | Referencia a la variable para almacenar el recuento de bytes escritos. |
| completed | **bool**\& | Referencia a la variable que se establece a true si el búfer de entrada se agotó y a false en caso contrario. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) método

Convierte caracteres a bytes.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| charCount | int | Tamaño del búfer de entrada. |
| bytes | **uint8_t** * | Búfer de bytes de destino. |
| byteCount | int | Tamaño del arreglo de destino. |
| flush | **bool** | Si es true, limpia el estado interno del codificador después del cálculo. |
| charsUsed | int\& | Referencia a la variable para almacenar el recuento de caracteres leídos. |
| bytesUsed | int\& | Referencia a la variable para almacenar el recuento de bytes escritos. |
| completed | **bool**\& | Referencia a la variable que se establece a true si el búfer de entrada se agotó y a false en caso contrario. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Encoder](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)