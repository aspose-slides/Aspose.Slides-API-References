---
title: Predicate
second_title: Aspose.Slides C++ API hivatkozás
description: Egy predikátumra mutató mutatót képvisel - egy meghívható entitást, amely egyetlen argumentumot fogad és bool értéket ad vissza.
type: docs
weight: 4187
url: /hu/system/predicate/
---
## Predikátum typedef


Egy predikátumra mutató mutatót képvisel - egy meghívható entitást, amely egyetlen argumentumot fogad és bool értéket ad vissza.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## Megjegyzések



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Kitölti a tömböt.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Létrehozza a predikátumot, amely egy 3-nál nagyobb tömbelemet ad vissza.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Megkeresi a tömb első elemét a létrehozott predikátummal, és kiírja.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
Ez a kódpélda a következő kimenetet adja:
5
*/
```

## Lásd még

* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)