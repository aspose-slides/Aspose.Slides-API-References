---
title: LINQ_ThenBy()
second_title: Referencia de la API de Aspose.Slides para C++
description: Realiza un ordenamiento subsecuente de los elementos en una secuencia en orden ascendente según una clave.
type: docs
weight: 27
url: /es/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) método

Realiza un ordenamiento subsecuente de los elementos en una secuencia en orden ascendente según una clave.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Key | El tipo de la clave devuelta por keySelector. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | Una función para extraer una clave de cada elemento. |

### Valor de retorno

[System::Linq::IOrderedEnumerable](../) cuyos elementos están ordenados según una clave.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) método

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IOrderedEnumerable](../)
* Clase [Func](../../../system/func/)
* Espacio de nombres [System::Linq](../../)
* Biblioteca [Aspose.Slides](../../../)