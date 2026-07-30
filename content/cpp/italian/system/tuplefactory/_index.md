---
title: TupleFactory
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce metodi statici per creare oggetti tuple.
type: docs
weight: 1366
url: /it/system/tuplefactory/
---
## TupleFactory classe

Fornisce metodi statici per creare oggetti tuple.

```cpp
class TupleFactory
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Crea un nuovo oggetto tuple. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Crea un nuovo 8-tuple. L'ottavo elemento è memorizzato all'interno di [Tuple](../tuple/). |
## Note



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
Questo esempio di codice produce il seguente output:
Elemento 1: 256
Elemento 2: 16
Elemento 3: 64
*/
```

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)