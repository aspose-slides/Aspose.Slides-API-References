---
title: ValueTask()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een lege, niet-geïnitieerde ValueTask.
type: docs
weight: 1
url: /nl/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() constructor

Construeert een lege, niet-geïnitieerde [ValueTask](../).

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Opmerkingen

De taak is niet voltooid en bevat geen resultaat. Proberen het resultaat op te halen zal een uitzondering veroorzaken.

## ValueTask::ValueTask(const TaskPtr\&) constructor

Construeert een [ValueTask](../) van een gedeelde pointer naar een [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | De taak om te omhullen. Kan null zijn voor een lege taak. |

## Opmerkingen

De [ValueTask](../) zal de status van de opgegeven taak weergeven.

## Zie ook

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)