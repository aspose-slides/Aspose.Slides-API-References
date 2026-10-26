---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un puntero a una función, método o un objeto funcional. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 287
url: /es/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> clase

Representa un puntero a una función, método o un objeto funcional. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ReturnType | El tipo de retorno de una función, método o puntero a objeto funcional que representa la clase |
| ArgumentTypes | La lista de argumentos de una función, método o puntero a objeto funcional que representa la clase |

## Métodos

| Método | Descripción |
| --- | --- |
|  [Delegate](./delegate/)() | Constructor predeterminado. Construye el objeto delegate que no apunta a nada. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Constructor de copia en movimiento. Toma la propiedad de una entidad a la que apunta el delegate especificado. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Constructor. Construye un objeto delegate a partir del puntero especificado a una función libre o método estático. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Constructor. Construye un delegate a partir del puntero especificado al objeto función generado por std::bind(). |
|  [Delegate](./delegate/)(int, T\&) | Constructor. Construye un delegate a partir del objeto función especificado. |
|  [Delegate](./delegate/)(long, T\&&) | Constructor en movimiento. Construye un delegate a partir del objeto función especificado. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Constructor. Construye un delegate que apunta al método no estático especificado del objeto especificado. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Constructor. Construye un delegate que apunta al método no estático especificado del objeto especificado. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Construye un objeto delegate que apunta a un objeto función std::function. |
| **bool** [Empty](./empty/)() const | Determina si el objeto delegate actual está vacío, p. ej., no apunta a ninguna entidad. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Invoca una función, método o objeto función al que apunta el objeto delegate actual. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Operador de asignación en movimiento. Toma la propiedad de una entidad a la que apunta el delegate especificado. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | Compara dos objetos delegate para verificar si apuntan a la misma entidad. |

## Observaciones

```cpp
#include "system/delegate.h"
#include <iostream>

// Declarar el delegado.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Asignar a la variable la dirección de la función PrintMessage.
  Message mes = Message(&PrintMessage);

  // Llamar a la función.
  mes();

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
¡Hola, mundo!
*/
```

## Véase también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)