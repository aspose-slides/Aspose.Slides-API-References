---
title: WhenAll()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un'attività che si completerà quando tutte le attività fornite saranno completate.
type: docs
weight: 196
url: /it/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) funzione


Crea un'attività che si completerà quando tutte le attività fornite saranno completate.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Le attività da attendere per il completamento. |

### Valore di ritorno

Un'attività che rappresenta il completamento di tutte le attività fornite.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) funzione


Crea un'attività che si completerà quando tutte le attività fornite saranno completate.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Le attività da attendere per il completamento. |

### Valore di ritorno

Un'attività che rappresenta il completamento di tutte le attività fornite.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) funzione


Crea un'attività che si completerà quando tutte le attività fornite saranno completate.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| TResult | Il tipo dei risultati delle attività completate. |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Le attività da attendere per il completamento. |

### Valore di ritorno

Un'attività che restituisce un array di tutti i risultati quando tutte le attività sono completate.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) funzione


Crea un'attività che si completerà quando tutte le attività fornite saranno completate.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| TResult | Il tipo dei risultati delle attività completate. |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Le attività da attendere per il completamento. |

### Valore di ritorno

Un'attività che restituisce un array di tutti i risultati quando tutte le attività sono completate.

## Vedi anche

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)