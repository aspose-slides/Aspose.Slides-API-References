---
title: ContinueWith()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Tworzy kontynuację, która jest wykonywana po zakończeniu zadania.
type: docs
weight: 118
url: /pl/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) metoda

Tworzy kontynuację, która jest wykonywana po zakończeniu zadania.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Akcja do wykonania po zakończeniu tego zadania |

### Wartość zwracana

TaskPtr Nowe zadanie reprezentujące kontynuację

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) metoda

Tworzy kontynuację, która jest wykonywana po zakończeniu zadania.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TResult | Typ wyniku zadania |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Funkcja zwracająca wynik po zakończeniu tego zadania |

### Wartość zwracana

RTaskPtr Nowe zadanie reprezentujące kontynuację

## Zobacz także

* Definicja typu [TaskPtr](../../../system/taskptr/)
* Definicja typu [Action](../../../system/action/)
* Definicja typu [RTaskPtr](../../../system/rtaskptr/)
* Klasa [Task](../)
* Klasa [Func](../../../system/func/)
* Przestrzeń nazw [System::Threading::Tasks](../../)
* Biblioteka [Aspose.Slides](../../../)