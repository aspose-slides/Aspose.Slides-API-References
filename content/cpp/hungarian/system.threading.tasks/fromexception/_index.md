---
title: FromException()
second_title: Aspose.Slides for C++ API referencia
description: Létrehoz egy feladatot, amely egy megadott kivétellel befejeződött.
type: docs
weight: 131
url: /hu/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) függvény


Létrehoz egy feladatot, amely egy megadott kivétellel befejeződött.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | A kivétel, amellyel a feladat befejeződik. |

### Visszatérési érték

Egy hibás feladat.

## System::Threading::Tasks::FromException(const Exception\&) függvény


Létrehoz egy feladatot, amely egy megadott kivétellel és eredménytípussal befejeződött.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TResult | A feladat eredményének típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | A kivétel, amellyel a feladat befejeződik. |

### Visszatérési érték

A megadott eredménytípussal rendelkező hibás feladat.

## Lásd még

* Típusdefiníció [TaskPtr](../../system/taskptr/)
* Típusdefiníció [Exception](../../system/exception/)
* Típusdefiníció [RTaskPtr](../../system/rtaskptr/)
* Névtere [System::Threading::Tasks](../)
* Könyvtár [Aspose.Slides](../../)