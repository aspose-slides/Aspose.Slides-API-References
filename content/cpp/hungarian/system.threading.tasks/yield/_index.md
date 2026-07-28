---
title: Yield()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehoz egy várható feladatot, amely aszinkron módon visszaadja a vezérlést a jelenlegi kontextusnak, amikor megvárják.
type: docs
weight: 222
url: /hu/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() függvény


Létrehoz egy várható feladatot, amely aszinkron módon visszaadja a vezérlést a jelenlegi kontextusnak, amikor megvárják.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```


### Visszatérési érték

Egy YieldAwaitable, amely megvárható a vezérlés átadásához.
## Megjegyzések



Ez a metódus hasznos egy aszinkron metódus kényszerítésére, hogy átadja a vezérlést, lehetővé téve, hogy más függőben lévő feladatok legyenek feldolgozva a folytatás előtt. 
## Lásd még

* Osztály [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Névtere [System::Threading::Tasks](../)
* Könyvtár [Aspose.Slides](../../)