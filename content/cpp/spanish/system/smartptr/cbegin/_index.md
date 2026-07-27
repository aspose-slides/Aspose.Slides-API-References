---
title: cbegin()
second_title: Referencia de API de Aspose.Slides para C++
description: Accesor del método cbegin() de una colección subyacente. Sólo se compila si SmartPtr_ es un tipo de especialización con el método cbegin().
type: docs
weight: 404
url: /es/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const método

Accesor para el método [cbegin()](./) de una colección subyacente. Sólo se compila si SmartPtr_ es el tipo de especialización con el método [cbegin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```

### Valor de retorno

iterador al comienzo de la colección

## Ver también

* Clase [SmartPtr](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)