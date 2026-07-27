---
title: operator==()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si el valor representado por el objeto actual es nulo.
type: docs
weight: 118
url: /es/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const método

Determina si el valor representado por el objeto actual es nulo.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```

### Valor devuelto

True si el valor representado por el objeto actual es nulo, de lo contrario - false

## Nullable::operator==(const T1\&) const método

Determina si el valor representado por el objeto actual es igual al valor especificado.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
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

True si el valor representado por el objeto actual es igual al valor especificado, de lo contrario - false

## Nullable::operator==(const Nullable\<T1\>\&) const método

Determina si el valor representado por el objeto actual es igual al valor representado por el objeto [Nullable](../) especificado.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
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

True si el valor representado por el objeto actual es igual al valor representado por el objeto [Nullable](../) especificado, de lo contrario - false

## Ver también

* Clase [Nullable](../)
* Estructura [IsNullable](../../isnullable/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)