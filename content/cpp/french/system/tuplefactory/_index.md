---
title: TupleFactory
second_title: Référence API Aspose.Slides pour C++
description: Fournit des méthodes statiques pour créer des objets tuple.
type: docs
weight: 1340
url: /fr/system/tuplefactory/
---
## TupleFactory classe


Fournit des méthodes statiques pour créer des objets tuple.

```cpp
class TupleFactory
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Crée un nouvel objet tuple. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Crée un nouveau 8-tuple. Le huitième élément est stocké dans [Tuple](../tuple/). |
## Remarques



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
Cet exemple de code produit la sortie suivante :
Item 1: 256
Item 2: 16
Item 3: 64
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)