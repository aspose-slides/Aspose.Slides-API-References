---
title: LINQ_Select()
second_title: Referencia de API de Aspose.Slides para C++
description: Transforma los elementos de una secuencia.
type: docs
weight: 248
url: /es/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) método

Transforma los elementos de una secuencia.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ResultType | El tipo del valor devuelto por el **selector**. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Una función de transformación. |

### Valor devuelto

Un [IEnumerable](../) que contiene los elementos devueltos por la función **selector**.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) método

Transforma cada elemento de una secuencia en una nueva forma incorporando el índice del elemento.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ResultType | El tipo del valor devuelto por el **selector**. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | Una función de transformación. |

### Valor devuelto

Un [IEnumerable](../) que contiene los elementos devueltos por la función **selector**.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) método

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) método

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IEnumerable](../)
* Clase [Func](../../../system/func/)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)