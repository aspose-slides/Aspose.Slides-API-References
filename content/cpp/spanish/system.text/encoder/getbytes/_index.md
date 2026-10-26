---
title: GetBytes()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene los bytes que resultan de codificar un búfer.
type: docs
weight: 53
url: /es/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) método


Obtiene los bytes que resultan de codificar un búfer.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |
| charIndex | int | Desplazamiento del array de origen. |
| charCount | int | Longitud del subarray de origen. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Búfer de bytes de destino. |
| byteIndex | int | Desplazamiento del búfer de destino. |
| flush | **bool** | Si true, limpia el estado interno del codificador tras el cálculo. |

### Return Value

Número de bytes escritos.

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) método


Obtiene los bytes que resultan de codificar un búfer.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| charCount | int | Longitud del array de origen. |
| bytes | **uint8_t** * | Búfer de bytes de destino. |
| byteCount | int | Tamaño del búfer de destino. |
| flush | **bool** | Si true, limpia el estado interno del codificador tras el cálculo. |

### Return Value

Número de bytes escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Encoder](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)