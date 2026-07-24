---
title: ValueTask()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert ein leeres, nicht initialisiertes ValueTask.
type: docs
weight: 1
url: /de/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() Konstruktor

Konstruiert ein leeres, nicht initialisiertes [ValueTask](../).

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Anmerkungen

Die Aufgabe ist nicht abgeschlossen und enthält kein Ergebnis. Der Versuch, das Ergebnis abzurufen, löst eine Ausnahme aus.

## ValueTask::ValueTask(const TaskPtr\&) Konstruktor

Konstruiert ein [ValueTask](../) aus einem gemeinsamen Zeiger auf ein [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | Die Aufgabe, die gewrappt werden soll. Kann null sein für eine leere Aufgabe. |

## Anmerkungen

Der [ValueTask](../) wird den Zustand der bereitgestellten Aufgabe darstellen.

## Siehe auch

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)