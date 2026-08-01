---
title: WaitAny()
second_title: Aspose.Slides voor C++ API-referentie
description: Wacht tot een van de opgegeven Task-objecten de uitvoering voltooid heeft.
type: docs
weight: 183
url: /nl/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) functie

Wacht tot een van de opgegeven [Task](../task/) objecten de uitvoering voltooid heeft.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Een array van [Task](../task/) instanties waarop gewacht moet worden. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Een [CancellationToken](../../system.threading/cancellationtoken/) om te observeren tijdens het wachten totdat de taken voltooid zijn. |

### Retourwaarde

De index van de voltooide taak in de takenarray.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) functie

Wacht tot een van de opgegeven [Task](../task/) objecten de uitvoering voltooid heeft.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Een array van [Task](../task/) instanties waarop gewacht moet worden. |

### Retourwaarde

De index van de voltooide taak in de takenarray.

## Zie ook

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Klasse [CancellationToken](../../system.threading/cancellationtoken/)
* Naamruimte [System::Threading::Tasks](../)
* Bibliotheek [Aspose.Slides](../../)