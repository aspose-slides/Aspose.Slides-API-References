---
title: ContinueWith()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří pokračování, které se spustí po dokončení úkolu.
type: docs
weight: 118
url: /cs/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) metoda


Vytvoří pokračování, které se spustí po dokončení úkolu.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Akce, která se vykoná, když je tento úkol dokončen |

### Návratová hodnota

TaskPtr Nový úkol představující pokračování

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) metoda


Vytvoří pokračování, které se spustí po dokončení úkolu.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TResult | Typ výsledku úkolu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Funkce, která získá výsledek, když je tento úkol dokončen |

### Návratová hodnota

RTaskPtr Nový úkol představující pokračování

## Viz také

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Třída [Task](../)
* Třída [Func](../../../system/func/)
* Jmenný prostor [System::Threading::Tasks](../../)
* Knihovna [Aspose.Slides](../../../)