---
title: LastIndexOf()
second_title: Referencia de API de Aspose.Slides para C++
description: Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista.
type: docs
weight: 469
url: /es/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const método

Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | const T\& | El objeto a localizar en la lista |

### Valor de retorno

El índice basado en cero de la última aparición de item dentro de todo el [List](../), si se encuentra; de lo contrario, -1.

## List::LastIndexOf(const T\&, int32_t) const método

Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro del rango de elementos en el [List](../) que se extiende desde el primer elemento hasta el índice especificado.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | const T\& | El objeto a localizar en la lista |
| index | **int32_t** | El índice inicial basado en cero de la búsqueda hacia atrás. |

### Valor de retorno

El índice basado en cero de la última aparición de item dentro del rango de elementos en el [List](../) que se extiende desde el primer elemento hasta index, si se encuentra; de lo contrario, -1.

## List::LastIndexOf(const T\&, int32_t, int32_t) const método

Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro del rango de elementos en el [List](../) que contiene el número especificado de elementos y termina en el índice especificado.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | const T\& | El objeto a localizar en el [List](../) |
| index | **int32_t** | El índice inicial basado en cero de la búsqueda hacia atrás. |
| count | **int32_t** | El número de elementos en la sección a buscar. |

### Valor de retorno

El índice basado en cero de la última aparición de item dentro del rango de elementos en el [List](../) que contiene count número de elementos y termina en index, si se encuentra; de lo contrario, -1.

## Ver también

* Clase [List](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)