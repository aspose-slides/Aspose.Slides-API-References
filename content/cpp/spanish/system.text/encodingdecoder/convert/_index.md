---
title: Convert()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte bytes a caracteres.
type: docs
weight: 1
url: /es/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method


Convierte bytes a caracteres.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes a decodificar. |
| byteCount | int | Tamaño del búfer de entrada. |
| chars | char_t * | Búfer de caracteres de destino. |
| charCount | int | Tamaño del arreglo de destino. |
| flush | **bool** | Si true, limpia el estado interno del decodificador después del cálculo. |
| bytesUsed | int\& | Referencia a la variable para almacenar el recuento de bytes leídos. |
| charsUsed | int\& | Referencia a la variable para almacenar el recuento de caracteres escritos. |
| completed | **bool**\& | Referencia a la variable que se establece en true si el búfer de entrada se agotó y en false en caso contrario. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method


Convierte bytes a caracteres.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |
| byteIndex | int | Desplazamiento del búfer de entrada. |
| byteCount | int | Tamaño del búfer de entrada. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Búfer de caracteres de destino. |
| charIndex | int | Desplazamiento del arreglo de destino. |
| charCount | int | Tamaño del arreglo de destino. |
| flush | **bool** | Si true, limpia el estado interno del decodificador después del cálculo. |
| bytesUsed | int\& | Referencia a la variable para almacenar el recuento de bytes leídos. |
| charsUsed | int\& | Referencia a la variable para almacenar el recuento de caracteres escritos. |
| completed | **bool**\& | Referencia a la variable que se establece en true si el búfer de entrada se agotó y en false en caso contrario. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EncodingDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)