---
title: Predicate
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Představuje ukazatel na predicate – volatelný objekt, který přijímá jeden argument a vrací hodnotu typu bool.
type: docs
weight: 4187
url: /cs/system/predicate/
---
## Predicate typedef

Představuje ukazatel na predicate – volatelný objekt, který přijímá jeden argument a vrací hodnotu typu bool.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## Poznámky



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Naplní pole.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Vytvoří predikát, který vrací prvek pole větší než 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Najde první prvek pole pomocí vytvořeného predikátu a vypíše jej.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
Tento příklad kódu produkuje následující výstup:
5
*/
```

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)