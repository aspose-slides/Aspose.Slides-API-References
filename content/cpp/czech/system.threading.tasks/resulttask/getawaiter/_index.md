---
title: GetAwaiter()
second_title: Aspose.Slides pro C++ referenční dokumentace API
description: Získá awaiter pro tento úkol výsledku pro použití s Await.
type: docs
weight: 53
url: /cs/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const metoda

Získá awaiter pro tento úkol výsledku pro použití s Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```

### Návratová hodnota

Runtime::CompilerServices::ResultTaskAwaiter<T> Instance awaiteru, která vrací výsledek
## Poznámky

Když je awaited, coroutine se obnoví s dostupnou hodnotou výsledku

## Viz také

* Třída [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Třída [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Knihovna [Aspose.Slides](../../../)