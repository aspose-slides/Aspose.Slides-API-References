---
title: ResultTask()
second_title: Aspose.Slides C++ API referenciája
description: Létrehoz egy ResultTask-ot egy olyan függvénnyel, amely visszaad egy értéket.
type: docs
weight: 1
url: /hu/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) constructor


Létrehoz egy [ResultTask](../)-t egy olyan függvénnyel, amely értéket ad vissza.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | A függvény, amely aszinkron módon végrehajtja és eredményt ad vissza. |

## ResultTask::ResultTask() constructor


Belső implementáció. Nem felhasználói kód számára.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Megjegyzések


Belső konstruktor nem inicializált eredményfeladatok létrehozásához 

## ResultTask::ResultTask(const T\&) constructor


Belső konstruktor eredményfeladatok létrehozásához megadott eredménnyel.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Lásd még

* Osztály [Func](../../../system/func/)
* Osztály [ResultTask](../)
* Névtér [System::Threading::Tasks](../../)
* Könyvtár [Aspose.Slides](../../../)