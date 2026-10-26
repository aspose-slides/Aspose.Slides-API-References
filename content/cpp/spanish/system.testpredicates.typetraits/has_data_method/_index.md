---
title: has_data_method
second_title: Referencia de API de Aspose.Slides para C++
description: "Comprueba si un tipo tiene el método data(). Si lo tiene, hereda de std::true_type; de lo contrario, hereda de std::false_type."
type: docs
weight: 1
url: /es/system.testpredicates.typetraits/has_data_method/
---
## has_data_method estructura

Comprueba si un tipo tiene el método data(). Si lo tiene, hereda de std::true_type; de lo contrario, hereda de std::false_type.

```cpp
template<typename T,typename Enable>class has_data_method : public std::false_type
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo a comprobar. |
| Enable | Argumento formal para que SFINAE funcione. |

## Ver también

* espacio de nombres [System::TestPredicates::TypeTraits](../)
* biblioteca [Aspose.Slides](../../)