---
title: TimerQueue
second_title: Riferimento API di Aspose.Slides per C++
description: Coda che gestisce gli oggetti Timer. Questa è solo un'implementazione. Gli oggetti Timer si registrano lì autonomamente, non è necessario farlo per usarli – usa l'API della classe Timer invece. Questo è un tipo singleton con la gestione della memoria effettuata tramite funzione(i) di accesso. Non dovresti mai creare istanze direttamente.
type: docs
weight: 261
url: /it/system.threading/timerqueue/
---
## TimerQueue classe

Coda che gestisce gli oggetti [Timer](../timer/). Questa è solo un'implementazione. [Timer](../timer/) oggetti si registrano lì autonomamente, non è necessario farlo per usarli – usa l'API della classe [Timer](../timer/) invece. Questo è un tipo singleton con la gestione della memoria effettuata da funzione(i) di accesso. Non dovresti mai creare istanze direttamente.

```cpp
class TimerQueue
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Registra il timer nella coda. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Elimina il timer dalla coda. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Singleton di implementazione. |
| static void [JoinWorkerThread](./joinworkerthread/)() | Unisce il thread di lavoro. Attende indefinitamente se necessario. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | Nessuna copia. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | Nessuna copia. |

## Vedi anche

* Spazio dei nomi [System::Threading](../)
* Libreria [Aspose.Slides](../../)