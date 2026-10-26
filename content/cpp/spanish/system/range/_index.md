---
title: Range
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa un rango con un índice de inicio y fin. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 1197
url: /es/system/range/
---
## Clase Range

Representa un rango con un índice de inicio y fin. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Métodos

| Método | Descripción |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | Crea un rango que comienza al inicio de la colección y termina en el índice final especificado. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | Determina si el rango actual es igual al rango especificado. |
| static constexpr [Range](./) [get_All](./get_all/)() | Devuelve un [Range](./) que representa toda la colección. |
| const [Index](../index/)\& [get_End](./get_end/)() const | Obtiene el índice End. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Obtiene el índice Start. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el rango actual. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | Calcula el desplazamiento inicial basado en cero y la longitud para la longitud de colección especificada. |
| constexpr [Range](./range/)() | Construye un rango vacío. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | Construye un [Range](./) a partir de los índices de inicio y fin especificados. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | Crea un rango que comienza en el índice de inicio especificado y se extiende hasta el final de la colección. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)