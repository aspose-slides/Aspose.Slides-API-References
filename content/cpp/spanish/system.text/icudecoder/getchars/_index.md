---
title: GetChars()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene los caracteres que resultan de decodificar un búfer.
type: docs
weight: 53
url: /es/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Obtiene los caracteres que resultan de decodificar un búfer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| byteIndex | int | Desplazamiento del búfer de entrada. |
| byteCount | int | Tamaño del búfer de entrada. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Búfer de caracteres de destino. |
| charIndex | int | Desplazamiento del arreglo de destino. |

### Valor de retorno

Número de caracteres escritos.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) method

Obtiene los caracteres que resultan de decodificar un búfer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| byteIndex | int | Desplazamiento del búfer de entrada. |
| byteCount | int | Tamaño del búfer de entrada. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Búfer de caracteres de destino. |
| charIndex | int | Desplazamiento del arreglo de destino. |
| flush | **bool** | Si es verdadero, limpia el estado interno del decodificador después del cálculo. |

### Valor de retorno

Número de caracteres escritos.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) method

Obtiene los caracteres que resultan de decodificar un búfer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| byteCount | int | Tamaño del búfer de entrada. |
| chars | char_t * | Búfer de caracteres de destino. |
| charCount | int | Tamaño del arreglo de destino. |
| flush | **bool** | Si es verdadero, limpia el estado interno del decodificador después del cálculo. |

### Valor de retorno

Número de caracteres escritos.

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ICUDecoder](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)