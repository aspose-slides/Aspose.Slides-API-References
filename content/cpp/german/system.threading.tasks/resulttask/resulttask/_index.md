---
title: ResultTask()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert ein ResultTask mit einer Funktion, die einen Wert zurückgibt.
type: docs
weight: 1
url: /de/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) Konstruktor


Konstruiert ein [ResultTask](../) mit einer Funktion, die einen Wert zurückgibt.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | Die Funktion, die asynchron ausgeführt wird und ein Ergebnis zurückgibt |

## ResultTask::ResultTask() Konstruktor


Interne Implementierung. Nicht für Benutzercode.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Bemerkungen


Interner Konstruktor zum Erzeugen nicht initialisierter ResultTask-Objekte 
## ResultTask::ResultTask(const T\&) Konstruktor


Interner Konstruktor zum Erzeugen von ResultTask-Objekten mit angegebenem Ergebnis.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Siehe auch

* Klasse [Func](../../../system/func/)
* Klasse [ResultTask](../)
* Namensraum [System::Threading::Tasks](../../)
* Bibliothek [Aspose.Slides](../../../)