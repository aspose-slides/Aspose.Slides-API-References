---
title: LINQ_SelectMany()
second_title: Referencia de la API de Aspose.Slides para C++
description: Proyecta cada elemento de una secuencia y combina las secuencias resultantes en una sola secuencia.
type: docs
weight: 300
url: /es/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) método

Proyecta cada elemento de una secuencia y combina las secuencias resultantes en una sola secuencia.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ResultType | El tipo del valor devuelto por el **selector**. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | Una función de transformación. |

### Valor de retorno

Un [IEnumerable](../) que contiene el resultado de invocar una función de proyección uno-a-muchos en cada elemento de la secuencia de entrada.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) método

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IEnumerable](../)
* Clase [Func](../../../system/func/)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)