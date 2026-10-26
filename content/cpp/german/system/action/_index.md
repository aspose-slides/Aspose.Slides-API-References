---
title: Action
second_title: Aspose.Slides für C++ API-Referenz
description: Delegatentyp, der Methoden referenziert, die keinen Rückgabewert haben.
type: docs
weight: 3602
url: /de/system/action/
---
## Action-Typdefinition


Delegatentyp, der Methoden referenziert, die keinen Rückgabewert haben.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Hinweise



```cpp
#include <system/action.h>

using namespace System;

// Die Funktion, die den übergebenen String ausgibt.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Erstelle eine Instanz von Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Rufe die Action auf.
  action(u"Hello, world!");

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
Hello, world!
*/
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)