---
title: LINQ_Average()
second_title: Referencia de API de Aspose.Slides para C++
description: Calcula el promedio de una secuencia de valores numéricos.
type: docs
weight: 365
url: /es/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() method


Calcula el promedio de una secuencia de valores numéricos.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```


### Valor devuelto

El promedio de los valores en la secuencia.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) method


Calcula el promedio de una secuencia de valores que se obtienen invocando una función de transformación en cada elemento de la secuencia de entrada.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ResultType | El tipo del valor devuelto por selector. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Una función de transformación que se aplicará a cada elemento. |

### Valor devuelto

El promedio de los valores proyectados.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## Ver también

* Clase [IEnumerable](../)
* Clase [Func](../../../system/func/)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)