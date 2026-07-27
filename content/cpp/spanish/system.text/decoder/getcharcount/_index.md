---
title: GetCharCount()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene el número de caracteres necesarios para decodificar un búfer.
type: docs
weight: 40
url: /es/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Obtiene el número de caracteres necesarios para decodificar un búfer.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |
| index | int | [Buffer](../../../system/buffer/) desplazamiento. |
| count | int | Número de bytes a decodificar. |

### Valor de retorno

Número de caracteres requeridos para decodificar el búfer.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method


Obtiene el número de caracteres necesarios para decodificar un búfer.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |
| index | int | [Buffer](../../../system/buffer/) desplazamiento. |
| count | int | Número de bytes a decodificar. |
| flush | **bool** | Si es true, limpia el estado interno del decodificador después del cálculo. |

### Valor de retorno

Número de caracteres requeridos para decodificar el búfer.

## Decoder::GetCharCount(const uint8_t *, int, bool) method


Obtiene el número de caracteres necesarios para decodificar un búfer.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes a decodificar. |
| count | int | Número de bytes a decodificar. |
| flush | **bool** | Si es true, limpia el estado interno del decodificador después del cálculo. |

### Valor de retorno

Número de caracteres requeridos para decodificar el búfer.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)