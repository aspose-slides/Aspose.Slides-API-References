---
title: CompareExchange()
second_title: Referencia de API de Aspose.Slides para C++
description: "Intercambia el valor de una variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado."
type: docs
weight: 79
url: /es/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T\&, T, T) método

Intercambia el valor de una variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de la variable. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location1 | T\& | Referencia a la variable a cambiar. |
| value | T | Valor a almacenar. |
| comparand | T | Valor con el que se compara el valor de la variable antes del intercambio. |

### Valor devuelto

Valor de la variable al iniciar la operación, independientemente de si fue cambiada o no.

## Interlocked::CompareExchange(T\&, T, T) método

Intercambia el valor de una variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado. No implementado.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de la variable. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location1 | T\& | Referencia a la variable a cambiar. |
| value | T | Valor a almacenar. |
| comparand | T | Valor con el que se compara el valor de la variable antes del intercambio. |

### Valor devuelto

Valor de la variable al iniciar la operación, independientemente de si fue cambiada o no.

## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) método

Intercambia el valor de una variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location1 | **int32_t**\& | Referencia a la variable a cambiar. |
| value | **int32_t** | Valor a almacenar. |
| comparand | **int32_t** | Valor con el que se compara el valor de la variable antes del intercambio. |
| succeeded | **bool**\& | Referencia a una variable que se establece en true si se realizó el intercambio y en false en caso contrario. |

### Valor devuelto

Valor de la variable al iniciar la operación, independientemente de si fue cambiada o no.

## Ver también

* Clase [Interlocked](../)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)