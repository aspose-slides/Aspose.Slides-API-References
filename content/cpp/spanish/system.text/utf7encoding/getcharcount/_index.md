---
title: GetCharCount()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtenga el número de caracteres necesarios para decodificar un búfer de bytes.
type: docs
weight: 79
url: /es/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) método

Obtenga el número de caracteres necesarios para decodificar un búfer de bytes.

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |
| index | int | Comienzo del segmento. |
| count | int | Tamaño del segmento. |

### Valor devuelto

Número de caracteres.

## UTF7Encoding::GetCharCount(const uint8_t *, int) método

Obtenga el número de caracteres necesarios para decodificar un búfer de bytes.

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes a decodificar. |
| count | int | Cantidad de bytes. |

### Valor devuelto

Número de caracteres.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) método

Obtenga el número de caracteres necesarios para decodificar un búfer de bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |
| index | int | Comienzo del segmento. |
| count | int | Tamaño del segmento. |

### Valor devuelto

Número de caracteres.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) método

Obtenga el número de caracteres necesarios para decodificar un búfer de bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |

### Valor devuelto

Número de caracteres.

## UTF7Encoding::GetCharCount(const uint8_t *, int) método

Obtenga el número de caracteres necesarios para decodificar un búfer de bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes a decodificar. |
| count | int | Cantidad de bytes. |

### Valor devuelto

Número de caracteres.

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [UTF7Encoding](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)