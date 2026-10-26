---
title: TupleFactory
second_title: Aspose.Slides a C++ API hivatkozása
description: Statikus metódusokat biztosít a tuple objektumok létrehozásához.
type: docs
weight: 1366
url: /hu/system/tuplefactory/
---
## TupleFactory osztály


Statikus metódusokat biztosít a tuple objektumok létrehozásához.

```cpp
class TupleFactory
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Új tuple objektumot hoz létre. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Új 8-tuple-t hoz létre. A 8. elem a(z) [Tuple](../tuple/)-ban van tárolva. |
## Megjegyzések



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
Ez a kódpélda a következő kimenetet állítja elő:
Elem 1: 256
Elem 2: 16
Elem 3: 64
*/
```

## Lásd még

* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)