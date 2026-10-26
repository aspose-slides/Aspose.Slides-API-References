---
title: ValueTuple
second_title: Referencia de API de Aspose.Slides para C++
description: Clase que representa una estructura de datos ValueTuple.
type: docs
weight: 1444
url: /es/system/valuetuple/
---
## ValueTuple clase

Clase que representa una [ValueTuple](./) estructura de datos.

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Métodos

| Método | Descripción |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Determina si el objeto actual y el especificado son idénticos. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | Obtiene la referencia al valor del componente del objeto [ValueTuple](./). |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | Obtiene el valor del componente del objeto [ValueTuple](./). |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Desconstruye el objeto en esta tupla de valores. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Devuelve una referencia al objeto [TypeInfo](../typeinfo/) que representa la información de tipo de la clase [ValueTuple](./). |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | Construye un objeto de tupla. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)