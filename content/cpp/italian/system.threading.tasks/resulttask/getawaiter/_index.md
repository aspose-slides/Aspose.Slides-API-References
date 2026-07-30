---
title: GetAwaiter()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene un awaiter per questo ResultTask da utilizzare con Await.
type: docs
weight: 53
url: /it/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const metodo

Ottiene un awaiter per questo ResultTask da utilizzare con Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```

### Valore di ritorno

Runtime::CompilerServices::ResultTaskAwaiter<T> Un'istanza awaiter che restituisce il risultato

## Osservazioni

Quando viene atteso, la coroutine riprenderà con il valore del risultato disponibile

## Vedi anche

* Classe [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Classe [ResultTask](../)
* Spazio dei nomi [System::Threading::Tasks](../../)
* Libreria [Aspose.Slides](../../../)