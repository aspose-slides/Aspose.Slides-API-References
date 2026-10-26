---
title: WeakPtrFromTypeParameter
second_title: Referencia de la API de Aspose.Slides para C++
description: Estructura de rasgo para convertir el tipo de argumento a un puntero débil, si es un tipo de puntero.
type: docs
weight: 2016
url: /es/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter estructura

Estructura de rasgo para convertir el tipo de argumento a un puntero débil, si es un tipo de puntero.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)