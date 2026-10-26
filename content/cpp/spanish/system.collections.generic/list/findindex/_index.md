---
title: FindIndex()
second_title: Referencia de API de Aspose.Slides para C++
description: Busca un elemento que cumpla con un predicado específico.
type: docs
weight: 404
url: /es/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) método


Busca un elemento que cumpla con un predicado específico.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicado para comprobar los elementos. |

### Valor devuelto

[Index](../../../system/index/) del elemento coincidente o -1 si no se encuentra.

## List::FindIndex(int, System::Predicate\<T\>) método


Busca un elemento que cumpla con un predicado específico.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) para iniciar la búsqueda desde. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicado para comprobar los elementos. |

### Valor devuelto

[Index](../../../system/index/) del elemento coincidente o -1 si no se encuentra.

## List::FindIndex(int, int, System::Predicate\<T\>) método


Busca un elemento que cumpla con un predicado específico.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) para iniciar la búsqueda desde. |
| count | int | Número de elementos a examinar. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicado para comprobar los elementos. |

### Valor devuelto

[Index](../../../system/index/) del elemento coincidente o -1 si no se encuentra.

## Ver también

* Typedef [Predicate](../../../system/predicate/)
* Clase [List](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)