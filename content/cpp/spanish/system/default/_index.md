---
title: Default()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la referencia a la única instancia construida por defecto del tipo de excepción.
type: docs
weight: 2224
url: /es/system/default/
---
## System::Default() función

Devuelve la referencia a la única instancia construida por defecto del tipo de excepción.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo cuya instancia se devuelve |

## System::Default() función

Devuelve la referencia a la única instancia construida por defecto del tipo que no es una excepción.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo cuya instancia se devuelve |

## Ver también

* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)