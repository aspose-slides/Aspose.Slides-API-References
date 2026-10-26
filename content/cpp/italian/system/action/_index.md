---
title: Action
second_title: Riferimento API di Aspose.Slides per C++
description: Tipo delegate che fa riferimento a metodi che non restituiscono alcun valore.
type: docs
weight: 3602
url: /it/system/action/
---
## Action typedef


Tipo delegate che fa riferimento a metodi che non restituiscono alcun valore.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Osservazioni



```cpp
#include <system/action.h>

using namespace System;

// La funzione che stampa la stringa passata.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Crea un'istanza di Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Chiama l'action.
  action(u"Hello, world!");

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
Hello, world!
*/
```

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)