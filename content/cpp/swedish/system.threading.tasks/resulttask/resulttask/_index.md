---
title: ResultTask()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ResultTask med en funktion som returnerar ett värde.
type: docs
weight: 1
url: /sv/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) konstruktor

Skapar en [ResultTask](../) med en funktion som returnerar ett värde.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | Funktionen som ska köras asynkront och som returnerar ett resultat |

## ResultTask::ResultTask() konstruktor

Intern implementation. Inte för användarkod.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Anmärkningar

Intern konstruktor för att skapa oinitierade resultatuppgifter

## ResultTask::ResultTask(const T\&) konstruktor

Intern konstruktor för att skapa resultatuppgifter med specificerat resultat.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Se även

* Klass [Func](../../../system/func/)
* Klass [ResultTask](../)
* Namnrymd [System::Threading::Tasks](../../)
* Bibliotek [Aspose.Slides](../../../)