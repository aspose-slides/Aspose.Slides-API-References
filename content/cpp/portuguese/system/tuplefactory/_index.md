---
title: TupleFactory
second_title: Referência da API Aspose.Slides para C++
description: Fornece métodos estáticos para criar objetos tuple.
type: docs
weight: 1366
url: /pt/system/tuplefactory/
---
## TupleFactory classe


Fornece métodos estáticos para criar objetos tuple.

```cpp
class TupleFactory
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Cria um novo objeto tuple. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Cria um novo 8-tuple. O 8º elemento é armazenado dentro [Tuple](../tuple/). |
## Observações



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
Este exemplo de código produz a seguinte saída:
Item 1: 256
Item 2: 16
Item 3: 64
*/
```

## Veja também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)