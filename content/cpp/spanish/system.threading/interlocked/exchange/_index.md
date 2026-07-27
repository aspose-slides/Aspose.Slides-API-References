---
title: Exchange()
second_title: Referencia de API de Aspose.Slides para C++
description: "Intercambia el valor en una variable: almacena el nuevo valor y devuelve el valor que la variable tenía inmediatamente antes de almacenarlo."
type: docs
weight: 66
url: /es/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) método

Intercambia el valor de una variable: almacena el nuevo valor y devuelve el valor que la variable tenía inmediatamente antes de almacenarlo.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de variable. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location1 | T\& | Referencia de variable a cambiar. |
| value | T | Valor a almacenar. |

### Valor de retorno

Valor de la variable justo antes de ser cambiada.

## Interlocked::Exchange(T\&, T) método

Intercambia el valor de una variable: almacena el nuevo valor y devuelve el valor que la variable tenía inmediatamente antes de almacenarlo. No implementado.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de variable. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location1 | T\& | Referencia de variable a cambiar. |
| value | T | Valor a almacenar. |

### Valor de retorno

Valor de la variable justo antes de ser cambiada.

## Ver también

* Clase [Interlocked](../)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)