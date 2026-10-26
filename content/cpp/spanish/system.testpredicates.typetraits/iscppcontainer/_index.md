---
title: IsCppContainer
second_title: Referencia de API de Aspose.Slides para C++
description: "Comprueba si un tipo específico es un contenedor estilo STL. Para ello, verifica la existencia de los tipos miembro iterator y const_iterator. Si ambos existen, hereda std::true_type; de lo contrario, hereda std::false_type."
type: docs
weight: 40
url: /es/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct


Comprueba si un tipo específico es un contenedor estilo STL. Para ello, verifica la existencia de los tipos miembro iterator y const_iterator. Si ambos existen, hereda std::true_type; de lo contrario, hereda std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo a comprobar. |
| Enable | Argumento formal para que SFINAE funcione. |

## Ver también

* Espacio de nombres [System::TestPredicates::TypeTraits](../)
* Biblioteca [Aspose.Slides](../../)