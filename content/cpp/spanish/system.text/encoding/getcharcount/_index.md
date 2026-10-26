---
title: GetCharCount()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el número de caracteres necesarios para decodificar un búfer de bytes.
type: docs
weight: 261
url: /es/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) método


Obtiene el número de caracteres necesarios para decodificar un búfer de bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |
| index | int | Inicio del segmento. |
| count | int | Tamaño del segmento. |

### Valor devuelto

Número de caracteres.

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) método


Obtiene el número de caracteres necesarios para decodificar un búfer de bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |

### Valor devuelto

Número de caracteres.

## Encoding::GetCharCount(const uint8_t *, int) método


Obtiene el número de caracteres necesarios para decodificar un búfer de bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes a decodificar. |
| count | int | Recuento de bytes. |

### Valor devuelto

Número de caracteres.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Encoding](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)