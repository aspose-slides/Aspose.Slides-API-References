---
title: operator-=()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una instancia de la clase Nullable que representa un valor nulo.
type: docs
weight: 248
url: /es/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) método


Devuelve una instancia de la clase [Nullable](../) que representa un valor nulo.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) método


Aplica [operator-=()](./) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T1 | El tipo del valor usado como el valor del lado derecho de [operator-=()](./) |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Una referencia constante al valor que se usa como valor del lado derecho del [operator-=()](./) aplicado al valor representado por el objeto actual. |

### Valor devuelto

Una referencia al propio objeto

## Nullable::operator-=(const Nullable\<T1\>\&) método


Aplica [operator-=()](./) al valor representado por el objeto actual usando el valor representado por el objeto [Nullable](../) especificado como argumento del lado derecho.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T1 | El tipo subyacente de un objeto [Nullable](../) cuyo valor representado se usa como argumento del lado derecho de [operator-=()](./) |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Una referencia constante al objeto [Nullable](../) cuyo valor representado se usa como argumento del lado derecho del [operator-=()](./) aplicado al valor representado por el objeto actual. |

### Valor devuelto

Una referencia al propio objeto

## Véase también

* Clase [Nullable](../)
* Estructura [IsNullable](../../isnullable/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)