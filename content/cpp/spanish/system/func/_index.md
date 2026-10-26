---
title: Func
second_title: Referencia de la API de Aspose.Slides para C++
description: "Delegado de función. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 859
url: /es/system/func/
---
## Func clase

Delegado de función. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Args | Argumentos de llamada, luego tipo de retorno obligatorio. |

## Métodos

| Método | Descripción |
| --- | --- |
|  [Func](./func/)() | Constructor predeterminado que crea null-Func. |
|  [Func](./func/)(T\&&) | Constructor que construye el objeto [Func](./) y asigna un valor (ya sea la devolución de llamada real o nullptr) a él. |
|  [Func](./func/)(const [Func](./)\&) | Constructor de copia. |
|  [Func](./func/)([Func](./)\&&) | Constructor de movimiento. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Asignación de copia. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Asignación de movimiento. |
|  [~Func](./~func/)() | Destructor. |

## Observaciones

```cpp
#include "system/func.h"
#include <iostream>

// Esta función acepta una instancia del delegado System::Func como parámetro.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Crea una instancia del delegado System::Func.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Pasa la instancia creada como argumento de función.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
1
4
9
*/
```

## Ver también

* Namespace [System](../)
* Library [Aspose.Slides](../../)