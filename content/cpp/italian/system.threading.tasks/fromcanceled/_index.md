---
title: FromCanceled()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un'attività che è stata completata a causa della cancellazione con il token specificato.
type: docs
weight: 118
url: /it/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled(const CancellationToken\&) funzione

Crea un'attività che è stata completata a causa della cancellazione con il token specificato.

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Il token di cancellazione che ha causato l'annullamento dell'attività. |

### Valore di ritorno

Un'attività annullata.

## Vedi anche

* Typedef [TaskPtr](../../system/taskptr/)
* Classe [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Libreria [Aspose.Slides](../../)