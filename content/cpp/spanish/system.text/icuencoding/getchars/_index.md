---
title: GetChars()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene los caracteres que resultan de decodificar un búfer de bytes.
type: docs
weight: 66
url: /es/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) método

Obtiene los caracteres que resultan de decodificar un búfer de bytes.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) para leer bytes de. |
| byte_count | int | Tamaño del búfer de entrada. |
| chars | char_t * | [Buffer](../../../system/buffer/) para colocar caracteres. |
| char_count | int | Tamaño del búfer de salida. |

### Valor devuelto

Número de caracteres escritos.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) método

Obtiene los caracteres que resultan de decodificar un búfer de bytes.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para leer bytes de. |
| byte_index | int | Desplazamiento del búfer de entrada. |
| byte_count | int | Tamaño del búfer de entrada. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) para colocar caracteres. |
| char_index | int | Desplazamiento del búfer de salida. |

### Valor devuelto

Número de caracteres escritos.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) método

Obtiene los caracteres que resultan de decodificar un búfer de bytes.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para leer bytes de. |
| index | int | Desplazamiento del búfer de entrada. |
| count | int | Tamaño del búfer de entrada. |

### Valor devuelto

[Buffer](../../../system/buffer/) de caracteres decodificados.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) método

Obtiene los caracteres que resultan de decodificar un búfer de bytes.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para leer bytes de. |

### Valor devuelto

[Buffer](../../../system/buffer/) de caracteres decodificados.

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) método

Obtiene los caracteres que resultan de decodificar un búfer de bytes.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) para leer bytes de. |
| byte_count | int | Tamaño del búfer de entrada. |
| chars | char_t * | [Buffer](../../../system/buffer/) para colocar caracteres. |
| char_count | int | Tamaño del búfer de salida. |

### Valor devuelto

Número de caracteres escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ICUEncoding](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)