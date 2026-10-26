---
title: ResultValueTask()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een lege, niet-geïinitialiseerde ResultValueTask.
type: docs
weight: 1
url: /nl/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() constructor

Construeert een lege, niet-geïnitialiseerde [ResultValueTask](../).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Opmerkingen

De taak is niet voltooid en bevat geen resultaat. Het proberen op te halen van het resultaat zal een uitzondering gooien.

## ResultValueTask::ResultValueTask(const T\&) constructor

Construeert een voltooide [ResultValueTask](../) met het opgegeven resultaat.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| result | const T\& | De resultaatwaarde om te verpakken in een voltooide taak. |
## Opmerkingen

Dit maakt een succesvol voltooide taak die de waarde onmiddellijk retourneert.

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) constructor

Construeert een [ResultValueTask](../) van een gedeelde pointer naar een ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | De taak om te verpakken. Kan null zijn voor een lege taak. |
## Opmerkingen

De [ResultValueTask](../) zal de status en het resultaat van de opgegeven taak weergeven.

## Zie ook

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Klasse [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)