---
title: begin()
second_title: Referencia de API de Aspose.Slides para C++
description: Accesor para el método begin() de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método begin().
type: docs
weight: 378
url: /es/system/smartptr/begin/
---
## SmartPtr::begin() método

Accesor para el método [begin()](./) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```

### Valor devuelto

iterator to the begin of collection

## SmartPtr::begin() const método

Accesor para el método [begin()](./) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```

### Valor devuelto

iterator to the begin of collection

## Ver también

* Clase [SmartPtr](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)