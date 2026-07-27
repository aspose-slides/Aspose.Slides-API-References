---
title: TrimEnd()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina el elemento especificado del final de un span tipado.
type: docs
weight: 378
url: /es/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) función

Elimina el elemento especificado del final de un span tipado.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
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

### Valor devuelto

Un nuevo span con el elemento especificado recortado del final

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) función

Elimina el elemento especificado del final de un span tipado mutable.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
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

### Valor devuelto

Un nuevo span con el elemento especificado recortado del final

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) función

Elimina los elementos especificados del final de un span tipado.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
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

### Valor devuelto

Un nuevo span con los elementos especificados recortados del final

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) función

Elimina los elementos especificados del final de un span tipado mutable.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
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

### Valor devuelto

Un nuevo span con los elementos especificados recortados del final

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) función

Elimina los caracteres de espacio en blanco del final de un span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El span de caracteres a recortar |

### Valor devuelto

Un nuevo span con los espacios en blanco recortados del final

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) función

Elimina los caracteres de espacio en blanco del final de un span de caracteres mutable.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | El span mutable de caracteres a recortar |

### Valor devuelto

Un nuevo span con los espacios en blanco recortados del final

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) función

Elimina el carácter especificado del final de un span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El span de caracteres a recortar |
| trimchar | char16_t | El carácter a recortar |

### Valor devuelto

Un nuevo span con el carácter especificado recortado del final

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) función

Elimina el carácter especificado del final de un span de caracteres mutable.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | El span mutable de caracteres a recortar |
| trimchar | char16_t | El carácter a recortar |

### Valor devuelto

Un nuevo span con el carácter especificado recortado del final

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) función

Elimina los caracteres especificados del final de un span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El span de caracteres a recortar |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Los caracteres a recortar |

### Valor devuelto

Un nuevo span con los caracteres especificados recortados del final

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) función

Elimina los caracteres especificados del final de un span de caracteres mutable.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | El span mutable de caracteres a recortar |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Los caracteres a recortar |

### Valor devuelto

Un nuevo span con los caracteres especificados recortados del final

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)