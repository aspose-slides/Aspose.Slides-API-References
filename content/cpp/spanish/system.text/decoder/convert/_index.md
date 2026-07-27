---
title: Convert()
second_title: Aspose.Slides para C++ Referencia de API
description: Convierte bytes a caracteres.
type: docs
weight: 79
url: /es/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method

Convierte bytes a caracteres.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |
| byteIndex | int | Desplazamiento del búfer de entrada. |
| byteCount | int | Tamaño del búfer de entrada. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Búfer de caracteres de destino. |
| charIndex | int | Desplazamiento del array de destino. |
| charCount | int | Tamaño del array de destino. |
| flush | **bool** | Si es true, limpia el estado interno del decodificador después del cálculo. |
| bytesUsed | int\& | Referencia a la variable para almacenar el recuento de bytes leídos. |
| charsUsed | int\& | Referencia a la variable para almacenar el recuento de caracteres escritos. |
| completed | **bool**\& | Referencia a la variable que se establecerá en true si el búfer de entrada se agotó y en false en caso contrario. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method

Convierte bytes a caracteres.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes a decodificar. |
| byteCount | int | Tamaño del búfer de entrada. |
| chars | char_t * | Búfer de caracteres de destino. |
| charCount | int | Tamaño del array de destino. |
| flush | **bool** | Si es true, limpia el estado interno del decodificador después del cálculo. |
| bytesUsed | int\& | Referencia a la variable para almacenar el recuento de bytes leídos. |
| charsUsed | int\& | Referencia a la variable para almacenar el recuento de caracteres escritos. |
| completed | **bool**\& | Referencia a la variable que se establecerá en true si el búfer de entrada se agotó y en false en caso contrario. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Decoder](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)