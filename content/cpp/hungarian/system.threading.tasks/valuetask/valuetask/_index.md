---
title: ValueTask()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy üres, nem inicializált ValueTask-ot.
type: docs
weight: 1
url: /hu/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() konstruktor

Létrehoz egy üres, inicializálatlan [ValueTask](../).

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Megjegyzés

A feladat nincs befejezve, és nem tartalmaz eredményt. Az eredmény lekérése kivételt fog dobni. 

## ValueTask::ValueTask(const TaskPtr\&) konstruktor

Létrehoz egy [ValueTask](../) egy megosztott mutatóból egy [Task](../../task/)-ra.

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | A becsomagolandó feladat. Lehet null egy üres feladathoz. |

## Megjegyzés

A [ValueTask](../) fogja képviselni a megadott feladat állapotát. 

## Lásd még

* Típusdefiníció [TaskPtr](../../../system/taskptr/)
* Osztály [ValueTask](../)
* Névtér [System::Threading::Tasks](../../)
* Könyvtár [Aspose.Slides](../../../)