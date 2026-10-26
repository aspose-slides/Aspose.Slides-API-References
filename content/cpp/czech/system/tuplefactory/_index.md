---
title: TupleFactory
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje statické metody pro vytváření objektů tuple.
type: docs
weight: 1366
url: /cs/system/tuplefactory/
---
## TupleFactory třída

Poskytuje statické metody pro vytváření objektů tuple.

```cpp
class TupleFactory
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Vytvoří nový objekt tuple. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Vytvoří novou 8-tici. 8. prvek je uložen uvnitř [Tuple](../tuple/). |
## Poznámky



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
Tento ukázkový kód vytiskne následující výstup:
Položka 1: 256
Položka 2: 16
Položka 3: 64
*/
```

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)