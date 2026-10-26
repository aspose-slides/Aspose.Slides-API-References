---
title: Action
second_title: Aspose.Slides C++ API referenciája
description: Delegált típus, amely olyan metódusokra hivatkozik, amelyeknek nincs visszatérési értékük.
type: docs
weight: 3602
url: /hu/system/action/
---
## Action típusdefiníció


Delegált típus, amely olyan metódusokra hivatkozik, amelyeknek nincs visszatérési értéke.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Megjegyzések



```cpp
#include <system/action.h>

using namespace System;

// A függvény, amely kiírja a kapott karakterláncot.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Action példányt hoz létre.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Az action meghívása.
  action(u"Hello, world!");

  return 0;
}
/*
Ez a kódpélda a következő kimenetet állítja elő:
Hello, world!
*/
```

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)