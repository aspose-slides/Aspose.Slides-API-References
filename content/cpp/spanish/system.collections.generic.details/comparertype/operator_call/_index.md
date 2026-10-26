---
title: operator()()
second_title: Referencia de API de Aspose.Slides para C++
description: Compara tipos de valor que implementan la interfaz IComparable.
type: docs
weight: 1
url: /es/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const método


Compara tipos de valor que implementan la interfaz [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | Tipo a comparar. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const Q\& | Valor del lado izquierdo. |
| b | const Q\& | Valor del lado derecho. |

### Valor devuelto

True si **a** se considera menor que **b**, false en caso contrario.

## ComparerType::operator()(const Q\&, const Q\&) const método


Compara tipos de valor primitivos y objetos que no implementan la interfaz [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | Tipo a comparar. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const Q\& | Valor del lado izquierdo. |
| b | const Q\& | Valor del lado derecho. |

### Valor devuelto

True si **a** se considera menor que **b**, false en caso contrario.

## ComparerType::operator()(const Q\&, const Q\&) const método


Compara tipos de punto flotante.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | Tipo a comparar. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const Q\& | Valor del lado izquierdo. |
| b | const Q\& | Valor del lado derecho. |

### Valor devuelto

True si **a** se considera menor que **b**, false en caso contrario.

## Ver también

* Clase [IComparable](../../../system/icomparable/)
* Estructura [has_method_compareto](../../has_method_compareto/)
* Estructura [ComparerType](../)
* Espacio de nombres [System::Collections::Generic::Details](../../)
* Biblioteca [Aspose.Slides](../../../)