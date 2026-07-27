---
title: GetBytes()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtenga los bytes que resultan de codificar un búfer de caracteres.
type: docs
weight: 248
url: /es/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) método

Obtenga los bytes que resultan de codificar un búfer de caracteres.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Parámetros

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |
| char_index | int | Inicio de la porción de caracteres. |
| char_count | int | Número de caracteres a convertir. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para colocar los caracteres. |
| byte_index | int | Desplazamiento del búfer de salida. |

### Valor devuelto

Número de bytes escritos.

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) método

Obtenga los bytes que resultan de codificar un búfer de caracteres.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Parámetros

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Caracteres a codificar. |
| char_index | int | Inicio de la porción de caracteres. |
| char_count | int | Número de caracteres a convertir. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) para colocar los caracteres. |
| byte_index | int | Desplazamiento del búfer de salida. |

### Valor devuelto

Número de bytes escritos.

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) método

Obtenga los bytes que resultan de codificar un búfer de caracteres.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Parámetros

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Caracteres a codificar. |
| char_index | int | Inicio de la porción de caracteres. |
| char_count | int | Número de caracteres a convertir. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) para colocar los caracteres. |
| byte_index | int | Desplazamiento del búfer de salida. |

### Valor devuelto

Número de bytes escritos.

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) método

Obtenga los bytes que resultan de codificar un búfer de caracteres.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Parámetros

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) para codificar. |
| char_index | int | Inicio de la porción de caracteres. |
| char_count | int | Número de caracteres a convertir. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para colocar los caracteres. |
| byte_index | int | Desplazamiento del búfer de salida. |

### Valor devuelto

Número de bytes escritos.

## Encoding::GetBytes(const String\&) método

Obtenga los bytes que resultan de codificar un búfer de caracteres.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Parámetros

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) para codificar. |

### Valor devuelto

[Buffer](../../../system/buffer/) que contiene la representación de los caracteres codificados.

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) método

Obtenga los bytes que resultan de codificar un búfer de caracteres.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Parámetros

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |
| index | int | Inicio de la porción de caracteres. |
| count | int | Número de caracteres a convertir. |

### Valor devuelto

[Buffer](../../../system/buffer/) que contiene la representación de los caracteres codificados.

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) método

Obtenga los bytes que resultan de codificar un búfer de caracteres.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Parámetros

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Caracteres a codificar. |
| index | int | Inicio de la porción de caracteres. |
| count | int | Número de caracteres a convertir. |

### Valor devuelto

[Buffer](../../../system/buffer/) que contiene la representación de los caracteres codificados.

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) método

Obtenga los bytes que resultan de codificar un búfer de caracteres.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Parámetros

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Caracteres a codificar. |
| index | int | Inicio de la porción de caracteres. |
| count | int | Número de caracteres a convertir. |

### Valor devuelto

[Buffer](../../../system/buffer/) que contiene la representación de los caracteres codificados.

## Encoding::GetBytes(ArrayPtr\<char_t\>) método

Obtenga los bytes que resultan de codificar un búfer de caracteres.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Parámetros

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |

### Valor devuelto

[Buffer](../../../system/buffer/) que contiene la representación de los caracteres codificados.

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) método

Obtenga los bytes que resultan de codificar un búfer de caracteres.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Parámetros

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| char_count | int | Número de caracteres a convertir. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) para colocar los caracteres. |
| byte_count | int | Tamaño del búfer de salida. |

### Valor devuelto

Número de bytes escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Encoding](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)