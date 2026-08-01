---
title: TupleFactory
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt statische methoden voor het maken van tuple-objecten.
type: docs
weight: 1366
url: /nl/system/tuplefactory/
---
## TupleFactory klasse


Biedt static methoden voor het maken van tuple-objecten.

```cpp
class TupleFactory
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Maakt een nieuw tuple-object aan. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Maakt een nieuw 8-tuple aan. Het 8e element wordt opgeslagen in [Tuple](../tuple/). |
## Opmerkingen



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
Deze code-voorbeeld produceert de volgende uitvoer:
Item 1: 256
Item 2: 16
Item 3: 64
*/
```

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)