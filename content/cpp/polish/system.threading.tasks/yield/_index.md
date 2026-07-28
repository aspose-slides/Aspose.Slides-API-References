---
title: Yield()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy zadanie awaitable, które asynchronicznie zwraca kontrolę do bieżącego kontekstu po wywołaniu await.
type: docs
weight: 222
url: /pl/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() funkcja


Tworzy zadanie awaitable, które asynchronicznie zwraca kontrolę do bieżącego kontekstu po wywołaniu await.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```


### Return Value

YieldAwaitable, który może być awaitowany, aby przekazać kontrolę.
## Remarks



Ta metoda jest przydatna do wymuszenia, aby metoda asynchroniczna przekazała kontrolę, umożliwiając przetworzenie innych oczekujących zadań przed kontynuacją. 
## See Also

* Klasa [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Przestrzeń nazw [System::Threading::Tasks](../)
* Biblioteka [Aspose.Slides](../../)