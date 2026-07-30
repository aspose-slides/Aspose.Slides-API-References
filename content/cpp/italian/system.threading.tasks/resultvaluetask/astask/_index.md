---
title: AsTask()
second_title: Riferimento API Aspose.Slides per C++
description: Converte questo ResultValueTask in un puntatore condiviso a ResultTask<T>.
type: docs
weight: 79
url: /it/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const metodo


Converte questo [ResultValueTask](../) in un puntatore condiviso a ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### Valore di ritorno

RTaskPtr<T> Un puntatore condiviso a ResultTask<T> che rappresenta questa operazione.
## Osservazioni



Se il [ResultValueTask](../) contiene un risultato diretto, crea un task completato con quel risultato. Se contiene un task, restituisce un puntatore condiviso a quel task. 

## Vedi anche

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Classe [ResultValueTask](../)
* Spazio dei nomi [System::Threading::Tasks](../../)
* Libreria [Aspose.Slides](../../../)