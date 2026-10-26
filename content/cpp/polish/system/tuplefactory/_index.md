---
title: TupleFactory
second_title: Aspose.Slides dla C++ – Referencja API
description: Udostępnia statyczne metody tworzenia obiektów krotek.
type: docs
weight: 1366
url: /pl/system/tuplefactory/
---
## TupleFactory klasa


Udostępnia statyczne metody do tworzenia obiektów krotek.

```cpp
class TupleFactory
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Tworzy nowy obiekt krotki. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Tworzy nową 8-krotkę. 8-ty element jest przechowywany wewnątrz [Tuple](../tuple/). |
## Uwagi



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
Ten przykład kodu generuje następujące wyjście:
Element 1: 256
Element 2: 16
Element 3: 64
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)