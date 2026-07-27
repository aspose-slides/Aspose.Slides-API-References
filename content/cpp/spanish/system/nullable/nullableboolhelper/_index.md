---
title: NullableBoolHelper()
second_title: Referencia de la API de Aspose.Slides para C++
description: Función auxiliar para comprobar si this y other no son nulos y llamar a una lambda en ese caso. Utilizada en implementaciones.
type: docs
weight: 105
url: /es/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const method

Función auxiliar para comprobar si **this** y **other** no son nulos y llamar a una lambda en ese caso. Usado en implementaciones.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Otro tipo nullable. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const T1\& | Otro valor nullable para comparar. |
| f | const std::function\<**bool**()>\& | Lambda a llamar si tanto **this** como **other** no son nulos. |
| default_if_both_are_null | **bool** | Valor devuelto si ambos valores son nulos. |

### Valor devuelto

false si **this** o **other** es nulo; **default_if_both_are_null** si ambos son nulos; resultado de la llamada a **f** si ambos no son nulos.

## Ver también

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)