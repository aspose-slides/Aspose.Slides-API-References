---
title: Action
second_title: Aspose.Slides för C++ API-referens
description: Delegattyp som refererar till metoder som inte har något returvärde.
type: docs
weight: 3602
url: /sv/system/action/
---
## Action typedef

Delegattyp som refererar till metoder som inte har något returvärde.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Anmärkningar

```cpp
#include <system/action.h>

using namespace System;

// Funktionen som skriver ut den överförda strängen.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Skapa en instans av Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Anropa action.
  action(u"Hello, world!");

  return 0;
}
/*
Detta kodexempel ger följande utdata:
Hello, world!
*/
```

## Se också

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)