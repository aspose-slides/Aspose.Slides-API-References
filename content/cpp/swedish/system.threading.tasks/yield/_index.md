---
title: Yield()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en väntbar uppgift som asynkront ger tillbaka kontrollen till den aktuella kontexten när den väntas på.
type: docs
weight: 222
url: /sv/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() funktion


Skapar en väntbar uppgift som asynkront ger tillbaka kontrollen till den aktuella kontexten när den väntas på.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```


### Returvärde

En YieldAwaitable som kan väntas på för att ge upp kontrollen.
## Anmärkningar



Denna metod är användbar för att tvinga en asynkron metod att ge upp kontrollen, vilket möjliggör bearbetning av annat väntande arbete innan fortsättning. 
## Se även

* Klass [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Namnrymd [System::Threading::Tasks](../)
* Bibliotek [Aspose.Slides](../../)