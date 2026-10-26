---
title: TupleFactory
second_title: Aspose.Slides para la referencia de API de C++
description: Proporciona métodos estáticos para crear objetos de tupla.
type: docs
weight: 1366
url: /es/system/tuplefactory/
---
## TupleFactory clase

Proporciona métodos estáticos para crear objetos de tupla.

```cpp
class TupleFactory
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Crea un nuevo objeto de tupla. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Crea una nueva 8-tupla. El octavo elemento se almacena dentro de [Tuple](../tuple/). |

## Observaciones

```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::TupleFactory::Create(256, 16, 64);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
Elemento 1: 256
Elemento 2: 16
Elemento 3: 64
*/
```

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)