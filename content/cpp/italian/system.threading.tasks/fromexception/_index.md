---
title: FromException()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un'attività che è stata completata con un'eccezione specificata.
type: docs
weight: 131
url: /it/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) funzione

Crea un'attività che è stata completata con un'eccezione specificata.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | L'eccezione con cui completare l'attività. |

### Valore di ritorno

Un'attività in errore.

## System::Threading::Tasks::FromException(const Exception\&) funzione

Crea un'attività che è stata completata con un'eccezione specificata e un tipo di risultato.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TResult | Il tipo del risultato dell'attività. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | L'eccezione con cui completare l'attività. |

### Valore di ritorno

Un'attività in errore con il tipo di risultato specificato.

## Vedi anche

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)