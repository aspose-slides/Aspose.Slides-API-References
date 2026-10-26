---
title: ResultValueTask()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en tom, oinitierad ResultValueTask.
type: docs
weight: 1
url: /sv/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() konstruktor


Skapar en tom, oinitierad [ResultValueTask](../).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Anmärkningar



Uppgiften är inte slutförd och innehåller inget resultat. Att försöka hämta resultatet kastar ett undantag. 

## ResultValueTask::ResultValueTask(const T\&) konstruktor


Skapar en slutförd [ResultValueTask](../) med det angivna resultatet.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| result | const T\& | Resultatvärdet att omsluta i en slutförd uppgift. |
## Anmärkningar



Detta skapar en framgångsrikt slutförd uppgift som omedelbart returnerar värdet. 

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) konstruktor


Skapar en [ResultValueTask](../) från en delad pekare till en ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | Uppgiften att omsluta. Kan vara null för en tom uppgift. |
## Anmärkningar



Den [ResultValueTask](../) kommer att representera tillståndet och resultatet för den angivna uppgiften. 

## Se även

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Klass [ResultValueTask](../)
* Namnrymd [System::Threading::Tasks](../../)
* Bibliotek [Aspose.Slides](../../../)