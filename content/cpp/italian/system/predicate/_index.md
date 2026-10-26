---
title: Predicate
second_title: Aspose.Slides per il riferimento API di C++
description: Rappresenta un puntatore a un predicato - un'entità invocabile che accetta un singolo argomento e restituisce un valore bool.
type: docs
weight: 4187
url: /it/system/predicate/
---
## Typedef del predicato


Rappresenta un puntatore a un predicato - un'entità invocabile che accetta un singolo argomento e restituisce un valore booleano.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## Osservazioni



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Riempie l'array.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Crea il predicato che restituisce un elemento dell'array maggiore di 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Trova il primo elemento dell'array usando il predicato creato e lo stampa.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
5
*/
```

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)