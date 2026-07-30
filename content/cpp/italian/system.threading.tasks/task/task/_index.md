---
title: Task()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruisce un Task con un'azione da eseguire.
type: docs
weight: 1
url: /it/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) costruttore

Costruisce un [Task](../) con un'azione da eseguire.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | L'azione da eseguire in modo asincrono |

## Task::Task(const Action<>\&, const CancellationToken\&) costruttore

Costruisce un [Task](../) con un'azione e un token di cancellazione.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | L'azione da eseguire in modo asincrono |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token per monitorare le richieste di cancellazione |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) costruttore

Costruisce un [Task](../) con un'azione con stato e un oggetto di stato.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | L'azione da eseguire (accetta l'oggetto di stato) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Oggetto di stato definito dall'utente passato all'azione |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) costruttore

Costruisce un [Task](../) con un'azione con stato, uno stato e un token di cancellazione.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | L'azione da eseguire (accetta l'oggetto di stato) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Oggetto di stato definito dall'utente passato all'azione |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token per monitorare le richieste di cancellazione |

## Task::Task() costruttore

Costruttore interno per creare task non inizializzati.

```cpp
System::Threading::Tasks::Task::Task()
```

## Vedi anche

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Task](../)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [Object](../../../system/object/)
* Namespace [System::Threading::Tasks](../../)
* Libreria [Aspose.Slides](../../../)