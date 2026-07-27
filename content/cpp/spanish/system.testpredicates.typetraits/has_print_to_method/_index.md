---
title: has_print_to_method
second_title: Referencia de API de Aspose.Slides para C++
description: "Comprueba si existe una sobrecarga de la función PrintTo que acepta el tipo dado como primer argumento. Si existe una sobrecarga, hereda std::true_type; de lo contrario, hereda std::false_type."
type: docs
weight: 27
url: /es/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method estructura

Comprueba si existe una sobrecarga de la función PrintTo que acepta el tipo dado como primer argumento. Si existe una sobrecarga, hereda std::true_type; de lo contrario, hereda std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo a comprobar. |
| Enable | Argumento formal para que SFINAE funcione. |

## Ver también

* Espacio de nombres [System::TestPredicates::TypeTraits](../)
* Biblioteca [Aspose.Slides](../../)