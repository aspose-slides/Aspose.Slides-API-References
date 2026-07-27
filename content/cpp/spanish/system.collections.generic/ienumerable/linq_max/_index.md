---
title: LINQ_Max()
second_title: Referencia de API de Aspose.Slides para C++
description: Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor máximo resultante.
type: docs
weight: 352
url: /es/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) método


Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor máximo resultante.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ResultType | El tipo del valor devuelto por selector. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Una función de transformación para aplicar a cada elemento. |

### Valor devuelto

El valor máximo en la secuencia.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) método




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Ver también

* Clase [Func](../../../system/func/)
* Clase [IEnumerable](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)