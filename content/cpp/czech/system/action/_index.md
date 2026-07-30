---
title: Action
second_title: Reference API Aspose.Slides pro C++
description: Typ delegáta, který odkazuje na metody, které nemají návratovou hodnotu.
type: docs
weight: 3602
url: /cs/system/action/
---
## Typ aliasu Action


Typ delegáta, který odkazuje na metody, které nemají návratovou hodnotu.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Poznámky



```cpp
#include <system/action.h>

using namespace System;

// Funkce, která vytiskne předaný řetězec.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Vytvořte instanci třídy Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Zavolejte akci.
  action(u"Hello, world!");

  return 0;
}
/*
Tento ukázkový kód vytiskne následující výstup:
Hello, world!
*/
```

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)