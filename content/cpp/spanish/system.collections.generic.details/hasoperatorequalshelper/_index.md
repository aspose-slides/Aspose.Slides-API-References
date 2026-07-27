---
title: HasOperatorEqualsHelper()
second_title: Referencia de API de Aspose.Slides para C++
description: Función auxiliar para determinar si una clase específica tiene el operador ==.
type: docs
weight: 235
url: /es/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) función

Función auxiliar para determinar si una clase específica tiene el operador ==.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo a comprobar. |
| Dummy | Argumento ficticio para la magia SFINAE. |

### Valor devuelto

Valor de std::true_type si operator == está presente y false en caso contrario.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) función

Función auxiliar para determinar si una clase específica tiene el operador ==.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### Valor devuelto

Valor de std::true_type si operator == está presente y false en caso contrario.

## Ver también

* Espacio de nombres [System::Collections::Generic::Details](../)
* Biblioteca [Aspose.Slides](../../)