---
title: Run()
second_title: Riferimento API Aspose.Slides per C++
description: Accoda il lavoro specificato per l'esecuzione nel pool di thread e restituisce un handle Task per quel lavoro.
type: docs
weight: 157
url: /it/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) function

Accoda il lavoro specificato per l'esecuzione nel pool di thread e restituisce un handle [Task](../task/) per quel lavoro.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Il lavoro da eseguire in modo asincrono. |

### Valore restituito

Un [Task](../task/) che rappresenta il lavoro accodato per l'esecuzione nel pool di thread.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) function

Accoda il lavoro specificato per l'esecuzione nel pool di thread e restituisce un handle [Task](../task/) per quel lavoro.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Il lavoro da eseguire in modo asincrono. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Un token di cancellazione che può essere usato per annullare il lavoro se non è ancora iniziato. |

### Valore restituito

Un [Task](../task/) che rappresenta il lavoro accodato per l'esecuzione nel pool di thread.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) function

Accoda il lavoro specificato per l'esecuzione nel pool di thread e restituisce un proxy per il [Task](../task/) restituito dalla funzione.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | Il lavoro da eseguire in modo asincrono, che restituisce un [Task](../task/). |

### Valore restituito

Un [Task](../task/) che rappresenta un proxy per il [Task](../task/) restituito dalla funzione.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) function

Accoda il lavoro specificato per l'esecuzione nel pool di thread e restituisce un handle Task<TResult> per quel lavoro.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TResult | Il tipo del risultato restituito dal task. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | Il lavoro da eseguire in modo asincrono. |

### Valore restituito

Un Task<TResult> che rappresenta il lavoro accodato per l'esecuzione nel pool di thread.

## Vedi anche

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Classe [CancellationToken](../../system.threading/cancellationtoken/)
* Classe [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)