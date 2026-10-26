---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa una colección de delegados. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 1093
url: /es/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> clase

Representa una colección de delegados. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use [System::SmartPtr](../smartptr/) clase para gestionar objetos de este tipo.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ReturnType | Tipo de retorno de las entidades invocables a las que apunta cada delegado en la colección |
| ArgumentTypes | Lista de argumentos de las entidades invocables a las que apunta cada delegado en la colección |

## Métodos

| Método | Descripción |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | NO IMPLEMENTADO. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Agrega el delegado especificado a la colección. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Agrega el objeto de función especificado a la colección de delegados. El objeto de función se convierte al tipo de delegado Callback antes de ser agregado a la colección. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Agrega el objeto MulticastDelegate especificado a la colección de delegados. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Agrega el método no estático especificado del objeto especificado a la colección de delegados. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Agrega el método no estático especificado del objeto especificado a la colección de delegados. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Elimina el delegado especificado de la colección de delegados. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Elimina el método no estático especificado del objeto especificado de la colección de delegados. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Elimina el método no estático especificado del objeto especificado de la colección de delegados. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Elimina el objeto MulticastDelegate especificado de la colección de delegados. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Elimina todos los delegados de la colección de delegados. |
| **bool** [empty](./empty/)() const | Determina si la colección de delegados está vacía. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | NO IMPLEMENTADO. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Invoca todos los delegados presentes actualmente en la colección de delegados. Los delegados se invocan en el mismo orden en que fueron agregados a la colección. El método bloquea mientras se ejecutan los delegados. |
| **bool** [IsNull](./isnull/)() const | Determina si la colección de delegados está vacía. |
|  [MulticastDelegate](./multicastdelegate/)() | Construye una colección vacía. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Equivalente al constructor por defecto. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Realiza una copia superficial de la colección de delegados. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Constructor de movimiento. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Construye una instancia y coloca el delegado especificado en la colección de delegados. |
|  [MulticastDelegate](./multicastdelegate/)(T) | Construye una instancia y coloca el valor especificado en la colección de delegados. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Construye una instancia y coloca el valor especificado en la colección de delegados. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Determina si la colección de delegados no está vacía. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Determina si dos instancias de MulticastDelegate - el objeto actual y el objeto especificado - son desiguales. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Invoca todos los delegados presentes actualmente en la colección de delegados. Los delegados se invocan en el mismo orden en que fueron agregados a la colección. El operador bloquea mientras se ejecutan los delegados. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Agrega el delegado especificado a la colección. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Elimina el delegado especificado de la colección de delegados. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Asigna la colección de delegados representada por el objeto especificado al objeto actual. Como resultado, ambos objetos apuntan a la misma colección de delegados. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Operador de asignación por movimiento. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Determina si la colección de delegados está vacía. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Determina si dos instancias de MulticastDelegate - el objeto actual y el objeto especificado - son iguales. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Limpia los callbacks contenidos que están vacíos (no llaman a nada). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Devuelve una referencia al objeto [TypeInfo](../typeinfo/) que representa la información de tipo de la clase MulticastDelegate. |
|  [~MulticastDelegate](./~multicastdelegate/)() | Destructor. |

## Definiciones de tipo

| Definición de tipo | Descripción |
| --- | --- |
| [Callback](./callback/) | El tipo de los delegados representados por la clase MulticastDelegate. |
| [Function](./function/) | El tipo de función relacionado con la firma del delegado. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)