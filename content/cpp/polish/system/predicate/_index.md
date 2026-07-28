---
title: Predicate
second_title: Aspose.Slides dla C++ referencja API
description: Reprezentuje wskaźnik na predykat - wywoływalny podmiot, który przyjmuje pojedynczy argument i zwraca wartość typu bool.
type: docs
weight: 4187
url: /pl/system/predicate/
---
## Definicja typu predykatu

Reprezentuje wskaźnik na predykat - wywoływalny podmiot, który przyjmuje pojedynczy argument i zwraca wartość typu bool.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## Uwagi


```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Wypełnij tablicę.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Utwórz predykat zwracający element tablicy większy niż 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Znajdź pierwszy element tablicy przy użyciu utworzonego predykatu i wypisz go.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
5
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)