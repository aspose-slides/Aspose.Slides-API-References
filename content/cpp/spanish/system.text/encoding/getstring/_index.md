---
title: GetString()
second_title: Referencia de la API de Aspose.Slides para C++
description: Decodifica un buffer de bytes en una cadena.
type: docs
weight: 313
url: /es/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) método


Decodifica un buffer de bytes en una cadena.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) para leer bytes de. |
| byte_count | int | Tamaño del buffer de entrada. |

### Valor devuelto

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) método


Decodifica un buffer de bytes en una cadena.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) para leer bytes de. |

### Valor devuelto

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(ArrayPtr\<uint8_t\>) método


Decodifica un buffer de bytes en una cadena.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para leer bytes de. |

### Valor devuelto

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) método


Decodifica un buffer de bytes en una cadena.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) para leer bytes de. |

### Valor devuelto

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) método


Decodifica un buffer de bytes en una cadena.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) para leer bytes de. |

### Valor devuelto

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) método


Decodifica un buffer de bytes en una cadena.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para leer bytes de. |
| index | int | Desplazamiento del buffer de entrada. |
| count | int | Tamaño del buffer de entrada. |

### Valor devuelto

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) método


Decodifica un buffer de bytes en una cadena.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) para leer bytes de. |
| index | int | Desplazamiento del buffer de entrada. |
| count | int | Tamaño del buffer de entrada. |

### Valor devuelto

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) método


Decodifica un buffer de bytes en una cadena.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) para leer bytes de. |
| index | int | Desplazamiento del buffer de entrada. |
| count | int | Tamaño del buffer de entrada. |

### Valor devuelto

[String](../../../system/string/) de caracteres decodificados.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [Encoding](../)
* Clase [ReadOnlySpan](../../../system/readonlyspan/)
* Espacio de nombres [System::Text](../../)
* Library [Aspose.Slides](../../../)