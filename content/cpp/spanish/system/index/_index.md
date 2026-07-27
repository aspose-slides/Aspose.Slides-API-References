---
title: Index
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa un índice en una colección. El índice puede ser desde el inicio o desde el final. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 1015
url: /es/system/index/
---
## Clase Index

Representa un índice en una colección. El índice puede ser desde el inicio o desde el final. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Métodos

| Método | Descripción |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | Determina si la instancia actual y el [Index](./) especificado representan la misma posición. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | Crea un [Index](./) que es relativo al final de la colección. |
| static constexpr [Index](./) [get_End](./get_end/)() | Obtiene un objeto [Index](./) que representa el final de una colección. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | Obtiene un valor que indica si el índice proviene del final. |
| static constexpr [Index](./) [get_Start](./get_start/)() | Obtiene un objeto [Index](./) que representa el inicio de una colección. |
| constexpr **int32_t** [get_Value](./get_value/)() const | Obtiene el valor del índice. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el índice actual. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | Convierte el [Index](./) actual en un desplazamiento desde el inicio de una colección con la longitud especificada. |
| constexpr [Index](./index/)() | Construye una instancia que representa el inicio de una colección. |
| constexpr [Index](./index/)(**int32_t**) | Construye una instancia que representa la posición especificada desde el inicio de una colección. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | Construye una instancia que representa el índice especificado. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)