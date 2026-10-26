---
title: AbstractEqual()
second_title: Referencia de API de Aspose.Slides para C++
description: Compara dos colecciones de tipo desconocido.
type: docs
weight: 14
url: /es/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) método

Compara dos colecciones de tipo desconocido.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento de la colección. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | colección LHS. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | colección RHS. |

### Valor devuelto

true si las colecciones coinciden (p. ej. ambas son nulas), o si sus tamaños coinciden y los elementos coinciden, false en caso contrario.

## Ver también

* Clase [ICollection](../../../system.collections.generic/icollection/)
* Estructura [TestCompare](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)