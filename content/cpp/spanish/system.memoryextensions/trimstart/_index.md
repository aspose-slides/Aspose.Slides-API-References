---
title: TrimStart()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina el elemento especificado del inicio de un span tipado.
type: docs
weight: 391
url: /es/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) función


Elimina el elemento especificado del inicio de un span tipado.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span a recortar |
| trimElement | const T\& | El elemento a recortar |

### Valor de retorno

Un nuevo span con el elemento especificado recortado del inicio

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) función


Elimina el elemento especificado del inicio de un span tipado mutable.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | El span mutable a recortar |
| trimElement | const T\& | El elemento a recortar |

### Valor de retorno

Un nuevo span con el elemento especificado recortado del inicio

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) función


Elimina los elementos especificados del inicio de un span tipado.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span a recortar |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Los elementos a recortar |

### Valor de retorno

Un nuevo span con los elementos especificados recortados del inicio

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) función


Elimina los elementos especificados del inicio de un span tipado mutable.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | El span mutable a recortar |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Los elementos a recortar |

### Valor de retorno

Un nuevo span con los elementos especificados recortados del inicio

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) función


Elimina los caracteres de espacio en blanco del inicio de un span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El span de caracteres a recortar |

### Valor de retorno

Un nuevo span con los espacios en blanco recortados del inicio

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) función


Elimina los caracteres de espacio en blanco del inicio de un span de caracteres mutable.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | El span de caracteres mutable a recortar |

### Valor de retorno

Un nuevo span con los espacios en blanco recortados del inicio

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) función


Elimina el carácter especificado del inicio de un span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El span de caracteres a recortar |
| trimchar | char16_t | El carácter a recortar |

### Valor de retorno

Un nuevo span con el carácter especificado recortado del inicio

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) función


Elimina el carácter especificado del inicio de un span de caracteres mutable.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | El span de caracteres mutable a recortar |
| trimchar | char16_t | El carácter a recortar |

### Valor de retorno

Un nuevo span con el carácter especificado recortado del inicio

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) función


Elimina los caracteres especificados del inicio de un span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El span de caracteres a recortar |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Los caracteres a recortar |

### Valor de retorno

Un nuevo span con los caracteres especificados recortados del inicio

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) función


Elimina los caracteres especificados del inicio de un span de caracteres mutable.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | El span de caracteres mutable a recortar |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Los caracteres a recortar |

### Valor de retorno

Un nuevo span con los caracteres especificados recortados del inicio

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)