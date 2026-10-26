---
title: ContinueWith()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy kontynuację, która jest wykonywana po zakończeniu zadania wynikowego.
type: docs
weight: 40
url: /pl/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) metoda


Tworzy kontynuację, która jest wykonywana po zakończeniu zadania wynikowego.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Action to execute when this task completes, receiving this result task |

### Wartość zwracana

TaskPtr Nowe zadanie reprezentujące kontynuację

## Uwagi



Akcja kontynuacji otrzymuje ten [ResultTask](../), aby uzyskać dostęp do wartości wyniku 

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) metoda


Tworzy kontynuację, która jest wykonywana po zakończeniu zadania wynikowego.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TNewResult | Result type of task continuation |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Function to get continuation result when this task completes, receiving this result task |

### Wartość zwracana

RTaskPtr Nowe zadanie reprezentujące kontynuację

## Uwagi



Funkcja kontynuacji otrzymuje ten [ResultTask](../), aby uzyskać dostęp do wartości wyniku 

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) metoda


Tworzy kontynuację, która jest wykonywana po zakończeniu zadania.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Action to execute when this task completes |

### Wartość zwracana

TaskPtr Nowe zadanie reprezentujące kontynuację

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) metoda


Tworzy kontynuację, która jest wykonywana po zakończeniu zadania.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TResult | A type of task result |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Function to get result when this task completes |

### Wartość zwracana

RTaskPtr Nowe zadanie reprezentujące kontynuację

## Zobacz także

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Klasa [ResultTask](../)
* Klasa [Func](../../../system/func/)
* Przestrzeń nazw [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)