---
title: operator!=()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si el valor representado por el objeto actual no es nulo.
type: docs
weight: 144
url: /es/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const método


Determina si el valor representado por el objeto actual no es nulo.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### Valor devuelto

True if the value represented by the current object is not null, otherwise - false

## Nullable::operator!=(const T1\&) const método


Determina si el valor representado por el objeto actual no es igual al valor especificado.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | The type of the value to compare with |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const T1\& | A constant reference to the value to compare with |

### Valor devuelto

True if the value represented by the current object is not equal to the specified value, otherwise - false

## Nullable::operator!=(const Nullable\<T1\>\&) const método


Determina si el valor representado por el objeto actual no es igual al valor representado por el objeto [Nullable](../) especificado.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | A constant reference to the [Nullable](../) object to compare with |

### Valor devuelto

True if the value represented by the current object is not equal to the value represented by the specified [Nullable](../) object, otherwise - false

## Véase también

* Clase [Nullable](../)
* Estructura [IsNullable](../../isnullable/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)