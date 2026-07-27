---
title: LINQ_Min()
second_title: Referencia de API de Aspose.Slides para C++
description: Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor mínimo resultante.
type: docs
weight: 339
url: /es/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) method


Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor mínimo resultante.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ResultType | El tipo del valor devuelto por selector. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Una función de transformación a aplicar a cada elemento. |

### Valor de retorno

El valor mínimo en la secuencia.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Ver también

* Clase [Func](../../../system/func/)
* Clase [IEnumerable](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)