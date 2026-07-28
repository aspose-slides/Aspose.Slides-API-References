---
title: ValueTask()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy pusty, niezainicjowany ValueTask.
type: docs
weight: 1
url: /pl/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() konstruktor

Tworzy pusty, niezainicjowany [ValueTask](../).

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Uwagi

Zadanie nie jest zakończone i nie zawiera wyniku. Próba pobrania wyniku spowoduje wyrzucenie wyjątku.

## ValueTask::ValueTask(const TaskPtr\&) konstruktor

Tworzy [ValueTask](../) ze współdzielonego wskaźnika do [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | Zadanie do opakowania. Może być null dla pustego zadania. |
## Uwagi

[ValueTask](../) będzie reprezentować stan dostarczonego zadania.

## Zobacz również

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)