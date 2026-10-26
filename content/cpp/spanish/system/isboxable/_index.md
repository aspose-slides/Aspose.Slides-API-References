---
title: IsBoxable
second_title: Referencia de API de Aspose.Slides para C++
description: Predicado de plantilla que verifica si el boxing del tipo especificado es compatible.
type: docs
weight: 1665
url: /es/system/isboxable/
---
## IsBoxable struct


Predicado de plantilla que verifica si el boxing del tipo especificado es compatible.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo a comprobar |


## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)