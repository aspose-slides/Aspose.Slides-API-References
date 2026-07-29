---
title: GetAwaiter()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar en awaiter för detta result task för användning med Await.
type: docs
weight: 53
url: /sv/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const metod


Hämtar en awaiter för detta result task för användning med Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```


### Returvärde

Runtime::CompilerServices::ResultTaskAwaiter<T> En awaiter-instans som returnerar resultatet
## Anmärkningar



När den awaitas, återupptas koroutinen med resultatvärdet tillgängligt 

## Se även

* Klass [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Klass [ResultTask](../)
* Namnrymd [System::Threading::Tasks](../../)
* Bibliotek [Aspose.Slides](../../../)