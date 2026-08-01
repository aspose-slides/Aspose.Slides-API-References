---
title: Predicate
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een pointer naar een predicaat voor - een aanroepbaar object dat één argument accepteert en een bool-waarde retourneert.
type: docs
weight: 4187
url: /nl/system/predicate/
---
## Predicate typedef

Stelt een pointer naar een predicaat voor - een aanroepbaar object dat één argument accepteert en een bool-waarde retourneert.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## Opmerkingen

```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Vul de array.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Maak het predicaat dat een array-element retourneert dat groter is dan 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Zoek het eerste element van de array met behulp van het gemaakte predicaat en druk het af.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
Dit codevoorbeeld geeft de volgende uitvoer:
5
*/
```

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)