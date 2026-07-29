---
title: ValueTask()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en tom, oinitierad ValueTask.
type: docs
weight: 1
url: /sv/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() konstruktör


Skapar ett tomt, oinitierat [ValueTask](../).

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Anmärkningar



Uppgiften är inte slutförd och innehåller inget resultat. Försök att hämta resultatet kommer att kasta ett undantag. 

## ValueTask::ValueTask(const TaskPtr\&) konstruktör


Skapar en [ValueTask](../) från en delad pekare till en [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | Uppgiften att omsluta. Kan vara null för en tom uppgift. |
## Anmärkningar



Den [ValueTask](../) kommer att representera tillståndet för den tillhandahållna uppgiften. 

## Se även

* Typedef [TaskPtr](../../../system/taskptr/)
* Klass [ValueTask](../)
* Namnrymd [System::Threading::Tasks](../../)
* Bibliotek [Aspose.Slides](../../../)