---
title: get_Result()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene il risultato dell'attività completata.
type: docs
weight: 66
url: /it/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() metodo


Ottiene il risultato dell'attività completata.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```


### Valore di ritorno

T Il valore di ritorno.
## Osservazioni


Se l'attività è basata su un ResultTask<T>, questo metodo attenderà il risultato e lo memorizzerà nella cache. Le chiamate successive restituiranno il valore memorizzato nella cache senza attendere. 

## Vedi anche

* Classe [ResultValueTask](../)
* Spazio dei nomi [System::Threading::Tasks](../../)
* Libreria [Aspose.Slides](../../../)