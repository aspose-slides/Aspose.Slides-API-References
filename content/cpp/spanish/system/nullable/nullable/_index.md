---
title: Nullable()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una instancia que representa un valor nulo.
type: docs
weight: 1
url: /es/system/nullable/nullable/
---
## Nullable::Nullable() constructor


Construye una instancia que representa un valor nulo.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) constructor


Construye una instancia que representa null.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) constructor


Construye una instancia de la clase [Nullable](../) que representa el valor especificado convertido (si es necesario) al valor del tipo subyacente T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo del valor especificado |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T1\& | Una referencia constante al valor que será representado por el nuevo objeto [Nullable](../) construido |

## Nullable::Nullable(const Nullable\<T1\>\&) constructor


Construye una instancia que representa un valor que está representado por el objeto [Nullable](../) especificado. El objeto nullable especificado puede representar un valor de tipo diferente al tipo subyacente de la instancia construida, en cuyo caso el valor representado se convierte a un valor del tipo T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo del valor representado por el objeto [Nullable](../) especificado |

## Véase también

* Clase [Nullable](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)