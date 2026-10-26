---
title: GetBytes()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtenga los bytes que resultan de codificar un búfer.
type: docs
weight: 53
url: /es/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) método

Obtiene los bytes que resultan de codificar un búfer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |
| charIndex | int | Desplazamiento del arreglo fuente. |
| charCount | int | Longitud del subarreglo fuente. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Búfer de bytes de destino. |
| byteIndex | int | Desplazamiento del búfer de destino. |
| flush | **bool** | Si es verdadero, limpia el estado interno del codificador después del cálculo. |

### Valor de retorno

Número de bytes escritos.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) método

Obtiene los bytes que resultan de codificar un búfer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| charCount | int | Longitud del arreglo fuente. |
| bytes | **uint8_t** * | Búfer de bytes de destino. |
| byteCount | int | Tamaño del búfer de destino. |
| flush | **bool** | Si es verdadero, limpia el estado interno del codificador después del cálculo. |

### Valor de retorno

Número de bytes escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ICUEncoder](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)