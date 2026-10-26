---
title: TupleFactory
second_title: Aspose.Slides für C++ API Referenz
description: Stellt statische Methoden zum Erstellen von Tupelobjekten bereit.
type: docs
weight: 1366
url: /de/system/tuplefactory/
---
## TupleFactory Klasse

Stellt statische Methoden zum Erstellen von Tupelobjekten bereit.

```cpp
class TupleFactory
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Erstellt ein neues Tupelobjekt. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Erstellt ein neues 8-Tupel. Das 8. Element wird in [Tuple](../tuple/) gespeichert. |
## Anmerkungen

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
Dieses Codebeispiel erzeugt die folgende Ausgabe:
Element 1: 256
Element 2: 16
Element 3: 64
*/
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)