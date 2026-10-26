---
title: operator=()
second_title: Referencia de API de Aspose.Slides para C++
description: Asigna null al objeto actual.
type: docs
weight: 14
url: /es/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) método


Asigna null al objeto actual.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```


### Valor devuelto

Un objeto [Nullable](../) que representa un valor nulo.

## Nullable::operator=(const T1\&) método


Reemplaza el valor representado actualmente por el objeto con el especificado.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| The | type of the new value to be represented by the current object |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const T1\& | The new value to be represented by the current object |

### Valor devuelto

Una referencia al propio objeto

## Nullable::operator=(const Nullable\<T1\>\&) método


Reemplaza el valor representado actualmente por el objeto con el especificado.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| The | type of the new value to be represented by the current object |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | The new value to be represented by the current object |

### Valor devuelto

Una referencia al propio objeto

## Ver también

* Clase [Nullable](../)
* Estructura [IsNullable](../../isnullable/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)