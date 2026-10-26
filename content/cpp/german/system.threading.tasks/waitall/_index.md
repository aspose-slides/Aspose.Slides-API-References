---
title: WaitAll()
second_title: Aspose.Slides für C++ API-Referenz
description: Wartet, bis alle bereitgestellten Task-Objekte die Ausführung abgeschlossen haben.
type: docs
weight: 170
url: /de/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) Funktion

Wartet, bis alle bereitgestellten [Task](../task/)-Objekte die Ausführung abgeschlossen haben.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Ein Array von [Task](../task/)-Instanzen, auf die gewartet wird. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Ein [CancellationToken](../../system.threading/cancellationtoken/), das während des Wartens auf den Abschluss der Tasks beobachtet wird. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) Funktion

Wartet, bis alle bereitgestellten [Task](../task/)-Objekte die Ausführung abgeschlossen haben.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Ein Array von [Task](../task/)-Instanzen, auf die gewartet wird. |

## Siehe auch

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Klasse [CancellationToken](../../system.threading/cancellationtoken/)
* Namensraum [System::Threading::Tasks](../)
* Bibliothek [Aspose.Slides](../../)