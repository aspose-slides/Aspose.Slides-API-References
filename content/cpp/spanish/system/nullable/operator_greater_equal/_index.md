---
title: operator>=()
second_title: Referencia de la API de Aspose.Slides para C++
description: Siempre devuelve false.
type: docs
weight: 183
url: /es/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const método


Siempre devuelve false.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### Valor devuelto

Siempre - false

## Nullable::operator>=(const T1\&) const método


Determina si el valor representado por el objeto actual es mayor o igual al valor representado por el objeto especificado aplicando [operator>=()](./) a estos valores.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo subyacente del valor con el que comparar el valor representado por el objeto actual |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const T1\& | Una referencia constante a un objeto con el que comparar el objeto actual |

### Valor devuelto

True si el valor representado por el objeto actual es mayor o igual al valor representado por el objeto especificado, de lo contrario - false

## Nullable::operator>=(const Nullable\<T1\>\&) const método


Determina si el valor representado por el objeto actual es mayor o igual al valor representado por el [Nullable](../) especificado aplicando [operator>=()](./) a estos valores.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo subyacente del objeto [Nullable](../) con el que comparar |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Una referencia constante al objeto [Nullable](../) con el que comparar |

### Valor devuelto

True si el valor representado por el objeto actual es mayor o igual al valor representado por el [Nullable](../) especificado, de lo contrario - false

## Ver también

* Clase [Nullable](../)
* Estructura [IsNullable](../../isnullable/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)