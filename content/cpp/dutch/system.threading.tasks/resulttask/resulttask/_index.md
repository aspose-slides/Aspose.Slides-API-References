---
title: ResultTask()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een ResultTask met een functie die een waarde retourneert.
type: docs
weight: 1
url: /nl/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) constructor


Construeert een [ResultTask](../) met een functie die een waarde retourneert.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | De functie die asynchroon moet worden uitgevoerd en een resultaat retourneert |

## ResultTask::ResultTask() constructor


Interne implementatie. Niet voor gebruikerscode.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Opmerkingen


Interne constructor voor het maken van niet-geïnitieerde result-tasks 
## ResultTask::ResultTask(const T\&) constructor


Interne constructor voor het maken van result-tasks met een gespecificeerd resultaat.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Zie ook

* Klasse [Func](../../../system/func/)
* Klasse [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Bibliotheek [Aspose.Slides](../../../)