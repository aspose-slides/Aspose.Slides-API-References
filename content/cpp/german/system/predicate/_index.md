---
title: Predicate
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen Zeiger auf ein Prädikat dar - ein aufrufbares Objekt, das ein einzelnes Argument akzeptiert und einen booleschen Wert zurückgibt.
type: docs
weight: 4187
url: /de/system/predicate/
---
## Prädikat-typedef


Stellt einen Zeiger auf ein Prädikat dar - ein aufrufbares Objekt, das ein einzelnes Argument akzeptiert und einen booleschen Wert zurückgibt.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## Hinweise



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Füllt das Array.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Erstellt das Prädikat, das ein Array-Element zurückgibt, das größer als 3 ist.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Findet das erste Element des Arrays mithilfe des erstellten Prädikats und gibt es aus.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
5
*/
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)