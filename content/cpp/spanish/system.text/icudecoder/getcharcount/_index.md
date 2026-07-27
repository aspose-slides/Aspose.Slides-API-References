---
title: GetCharCount()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene el número de caracteres necesarios para decodificar un buffer.
type: docs
weight: 40
url: /es/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) método

Obtiene el número de caracteres necesarios para decodificar un buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes para decodificar. |
| index | int | [Buffer](../../../system/buffer/) desplazamiento. |
| count | int | Número de bytes a decodificar. |

### Valor de retorno

Número de caracteres requeridos para decodificar el buffer.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) método

Obtiene el número de caracteres necesarios para decodificar un buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes para decodificar. |
| index | int | [Buffer](../../../system/buffer/) desplazamiento. |
| count | int | Número de bytes a decodificar. |
| flush | **bool** | Si es true, limpia el estado interno del decodificador después del cálculo. |

### Valor de retorno

Número de caracteres requeridos para decodificar el buffer.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) método

Obtiene el número de caracteres necesarios para decodificar un buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes para decodificar. |
| count | int | Número de bytes a decodificar. |
| flush | **bool** | Si es true, limpia el estado interno del decodificador después del cálculo. |

### Valor de retorno

Número de caracteres requeridos para decodificar el buffer.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ICUDecoder](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)