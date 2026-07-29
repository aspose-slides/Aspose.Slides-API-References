---
title: TupleFactory
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller statiska metoder för att skapa tuple-objekt.
type: docs
weight: 1366
url: /sv/system/tuplefactory/
---
## TupleFactory klass

Tillhandahåller statiska metoder för att skapa tuple-objekt.

```cpp
class TupleFactory
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Skapar ett nytt tuple-objekt. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Skapar en ny 8-tuple. Det 8:e elementet lagras i [Tuple](../tuple/). |
## Anmärkningar



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
Det här kodexemplet producerar följande utskrift:
Objekt 1: 256
Objekt 2: 16
Objekt 3: 64
*/
```

## Se även

* namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)