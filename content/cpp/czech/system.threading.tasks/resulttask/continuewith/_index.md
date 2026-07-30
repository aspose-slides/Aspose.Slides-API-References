---
title: ContinueWith()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří pokračování, které se spustí po dokončení úkolu s výsledkem.
type: docs
weight: 40
url: /cs/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) metoda

Vytvoří pokračování, které se spustí po dokončení úkolu s výsledkem.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Akce, která se provede po dokončení tohoto úkolu a přijme tento úkol s výsledkem |
|  |  |  |

### Návratová hodnota

TaskPtr Nový úkol představující pokračování

## Poznámky

Akce pokračování přijímá tento [ResultTask](../) pro přístup k hodnotě výsledku

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) metoda

Vytvoří pokračování, které se spustí po dokončení úkolu s výsledkem.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TNewResult | Typ výsledku pokračování úkolu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Funkce, která získá výsledek pokračování po dokončení tohoto úkolu a přijme tento úkol s výsledkem |

### Návratová hodnota

RTaskPtr Nový úkol představující pokračování

## Poznámky

Funkce pokračování přijímá tento [ResultTask](../) pro přístup k hodnotě výsledku

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) metoda

Vytvoří pokračování, které se spustí po dokončení úkolu.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Akce, která se provede po dokončení tohoto úkolu |

### Návratová hodnota

TaskPtr Nový úkol představující pokračování

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) metoda

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
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Funkce, která získá výsledek po dokončení tohoto úkolu |

### Návratová hodnota

RTaskPtr Nový úkol představující pokračování

## Viz také

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Třída [ResultTask](../)
* Třída [Func](../../../system/func/)
* Jmenný prostor [System::Threading::Tasks](../../)
* Knihovna [Aspose.Slides](../../../)