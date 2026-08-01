---
title: Action
second_title: Aspose.Slides voor C++ API-referentie
description: Delegatetype die verwijst naar methoden die geen retourwaarde hebben.
type: docs
weight: 3602
url: /nl/system/action/
---
## Actie typedef

Delegatetype die verwijst naar methoden die geen retourwaarde hebben.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Opmerkingen



```cpp
#include <system/action.h>

using namespace System;

// De functie die de meegegeven string afdrukt.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Maak een instantie van Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Roep de actie aan.
  action(u"Hello, world!");

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende uitvoer:
Hallo, wereld!
*/
```

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)