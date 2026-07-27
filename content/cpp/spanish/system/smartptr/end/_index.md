---
title: end()
second_title: Aspose.Slides para C++ Referencia de API
description: Accesor para el método end() de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método end().
type: docs
weight: 391
url: /es/system/smartptr/end/
---
## SmartPtr::end() método


Accesor para el método [end()](./) de una colección subyacente. Sólo se compila si SmartPtr_ es un tipo de especialización con el método [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```


### Valor devuelto

iterador al final de la colección

## SmartPtr::end() const método


Accesor para el método [end()](./) de una colección subyacente. Sólo se compila si SmartPtr_ es un tipo de especialización con el método [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```


### Valor devuelto

iterador al final de la colección

## Ver también

* Clase [SmartPtr](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)