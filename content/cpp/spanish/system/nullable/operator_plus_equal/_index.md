---
title: operator+=()
second_title: Referencia de API de Aspose.Slides para C++
description: Restablece el objeto actual para que represente un valor nulo.
type: docs
weight: 235
url: /es/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) método

Restablece el objeto actual para que represente un valor nulo.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```

### Valor devuelto

Una copia del propio objeto

## Nullable::operator+=(const T1\&) método

Aplica [operator+=()](./) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo del valor usado como valor del lado derecho de [operator+=()](./) |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const T1\& | Una referencia constante al valor que se usa como argumento del lado derecho del [operator+=()](./) aplicado al valor representado por el objeto actual. |

### Valor devuelto

Una referencia al propio objeto

## Nullable::operator+=(const Nullable\<T1\>\&) método

Aplica [operator+=()](./) al valor representado por el objeto actual usando el valor representado por el objeto [Nullable](../) especificado como argumento del lado derecho.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo subyacente de un objeto [Nullable](../) cuyo valor representado se usa como argumento del lado derecho de [operator+=()](./) |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Una referencia constante al objeto [Nullable](../) cuyo valor representado se usa como argumento del lado derecho del [operator+=()](./) aplicado al valor representado por el objeto actual. |

### Valor devuelto

Una referencia al propio objeto

## Ver también

* Clase [Nullable](../)
* Estructura [IsNullable](../../isnullable/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)