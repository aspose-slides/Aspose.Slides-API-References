---
title: WaitAny()
second_title: Aspose.Slides für C++ API-Referenz
description: Wartet darauf, dass eines der bereitgestellten Task-Objekte die Ausführung beendet.
type: docs
weight: 183
url: /de/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) function


Wartet darauf, dass eines der bereitgestellten [Task](../task/) Objekte die Ausführung beendet.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Ein Array von [Task](../task/)-Instanzen, auf das gewartet wird. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Ein [CancellationToken](../../system.threading/cancellationtoken/), das während des Wartens auf den Abschluss der Tasks beobachtet wird. |

### Rückgabewert

Der Index der abgeschlossenen Aufgabe im Aufgaben-Array.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) function


Wartet darauf, dass eines der bereitgestellten [Task](../task/) Objekte die Ausführung beendet.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Ein Array von [Task](../task/)-Instanzen, auf das gewartet wird. |

### Rückgabewert

Der Index der abgeschlossenen Aufgabe im Aufgaben-Array.

## Siehe auch

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Klasse [CancellationToken](../../system.threading/cancellationtoken/)
* Namensraum [System::Threading::Tasks](../)
* Bibliothek [Aspose.Slides](../../)