---
title: Yield()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří awaitovatelný úkol, který asynchronně předá řízení zpět aktuálnímu kontextu, když je awaitován.
type: docs
weight: 222
url: /cs/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() funkce


Vytvoří awaitovatelný úkol, který asynchronně předá řízení zpět aktuálnímu kontextu, když je awaitován.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```


### Návratová hodnota

YieldAwaitable, který může být awaitován k předání řízení.
## Poznámky



Tato metoda je užitečná pro vynucení, aby asynchronní metoda předala řízení, což umožní zpracování dalších čekajících úkolů před pokračováním. 
## Viz také

* Třída [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Jmenný prostor [System::Threading::Tasks](../)
* Knihovna [Aspose.Slides](../../)