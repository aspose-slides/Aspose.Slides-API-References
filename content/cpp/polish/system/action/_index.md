---
title: Action
second_title: Aspose.Slides dla C++ Referencja API
description: Typ delegata, który odwołuje się do metod nie zwracających wartości.
type: docs
weight: 3602
url: /pl/system/action/
---
## Action definicja typu


Typ delegata, który odwołuje się do metod nie zwracających wartości.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Uwagi



```cpp
#include <system/action.h>

using namespace System;

// Funkcja, która wypisuje przekazany ciąg znaków.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Utwórz instancję Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Wywołaj akcję.
  action(u"Hello, world!");

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
Hello, world!
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)