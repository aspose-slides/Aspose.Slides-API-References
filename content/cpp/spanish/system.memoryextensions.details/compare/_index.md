---
title: Compare()
second_title: Referencia de API de Aspose.Slides para C++
description: Compara dos punteros inteligentes.
type: docs
weight: 1
url: /es/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) función

Compara dos punteros inteligentes.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del primer puntero inteligente |
| U | Tipo del segundo puntero inteligente |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Primer puntero inteligente |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Segundo puntero inteligente |

### Valor devuelto

[Comparison](../../system/comparison/) resultado (0 si son iguales, -1 si a < b, 1 si a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) función

Compara dos valores aritméticos.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo aritmético |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const T\& | Primer valor |
| b | const T\& | Segundo valor |

### Valor devuelto

[Comparison](../../system/comparison/) resultado (0 si son iguales, -1 si a < b, 1 si a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) función

Compara un puntero inteligente con un valor.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo apuntado por el puntero inteligente |
| U | Tipo del valor |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Puntero inteligente |
| b | const U\& | Valor |

### Valor devuelto

[Comparison](../../system/comparison/) resultado (0 si son iguales, -1 si a < b, 1 si a > b)

## Ver también

* Typedef [SharedPtr](../../system/sharedptr/)
* Espacio de nombres [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)