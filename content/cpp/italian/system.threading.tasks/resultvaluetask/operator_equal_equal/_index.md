---
title: operator==()
second_title: Riferimento API di Aspose.Slides per C++
description: Operatore di uguaglianza per ResultValueTask.
type: docs
weight: 131
url: /it/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const metodo


Operatore di uguaglianza per [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | L'altro [ResultValueTask](../) da confrontare con questa istanza. |

### Valore di ritorno

bool True se entrambi i task hanno lo stesso valore di risultato o fanno riferimento allo stesso task sottostante; altrimenti, false.
## Osservazioni



Se una delle due istanze contiene un valore di risultato diretto, confronta i risultati direttamente. Altrimenti, confronta i puntatori al task sottostante. 
## Vedi anche

* Classe [ResultValueTask](../)
* Spazio dei nomi [System::Threading::Tasks](../../)
* Libreria [Aspose.Slides](../../../)