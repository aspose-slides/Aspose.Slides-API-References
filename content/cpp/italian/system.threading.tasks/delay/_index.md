---
title: Delay()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un'operazione che si completa dopo un ritardo temporale.
type: docs
weight: 105
url: /it/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) funzione


Crea un'operazione che si completa dopo un ritardo temporale.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Il numero di millisecondi da attendere prima di completare l'operazione restituita, oppure -1 per attendere indefinitamente. |

### Valore di ritorno

Un'operazione che rappresenta il ritardo temporale.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) funzione


Crea un'operazione che si completa dopo un ritardo temporale e può essere annullata.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Il numero di millisecondi da attendere prima di completare l'operazione restituita, oppure -1 per attendere indefinitamente. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Il token di cancellazione che può essere usato per annullare il ritardo. |

### Valore di ritorno

Un'operazione che rappresenta il ritardo temporale.

## Vedi anche

* Typedef [TaskPtr](../../system/taskptr/)
* Classe [CancellationToken](../../system.threading/cancellationtoken/)
* Spazio dei nomi [System::Threading::Tasks](../)
* Libreria [Aspose.Slides](../../)