---
title: WaitAll()
second_title: Aspose.Slides voor C++ API-referentie
description: Wacht tot alle opgegeven Task-objecten de uitvoering hebben voltooid.
type: docs
weight: 170
url: /nl/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) functie

Wacht tot al de opgegeven [Task](../task/)-objecten de uitvoering hebben voltooid.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Een array van [Task](../task/)-instanties waarop gewacht moet worden. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Een [CancellationToken](../../system.threading/cancellationtoken/) om te observeren terwijl gewacht wordt op het voltooien van de taken. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) functie

Wacht tot al de opgegeven [Task](../task/)-objecten de uitvoering hebben voltooid.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Een array van [Task](../task/)-instanties waarop gewacht moet worden. |

## Zie ook

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)