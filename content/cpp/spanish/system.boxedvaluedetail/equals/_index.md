---
title: Equals()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina la igualdad del valor especificado usando el operador==().
type: docs
weight: 66
url: /es/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) función


Determina la igualdad del valor especificado usando [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| The | tipo de los valores comparados |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value1 | T | The first comparand |
| value2 | T | The second comparand |

### Valor devuelto

Verdadero si los valores especificados son iguales según lo determina [operator==()](../../system/operator_equal_equal/), de lo contrario - false

## System::BoxedValueDetail::Equals(T, T) función


Determina la igualdad del valor especificado usando el método [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| The | tipo de los valores comparados |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value1 | T | The first comparand |
| value2 | T | The second comparand |

### Valor devuelto

Verdadero si los valores especificados son iguales según lo determina el método [Equals()](./), de lo contrario - false

## Ver también

* Espacio de nombres [System::BoxedValueDetail](../)
* Biblioteca [Aspose.Slides](../../)