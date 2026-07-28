---
title: Delay()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehoz egy feladatot, amely egy időeltelt után befejeződik.
type: docs
weight: 105
url: /hu/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) függvény


Létrehoz egy feladatot, amely egy időeltelt után befejeződik.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | A visszaadott feladat befejezése előtt várandó ezredmásodpercek száma, vagy -1 a határozatlan ideig történő várakozás. |

### Visszatérési érték

Egy feladat, amely az időelteltet képviseli.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken&) függvény


Létrehoz egy feladatot, amely egy időeltelt után befejeződik, és leállítható.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | A visszaadott feladat befejezése előtt várandó ezredmásodpercek száma, vagy -1 a határozatlan ideig történő várakozás. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | A leállítási token, amelyet a késleltetés megszakításához lehet használni. |

### Visszatérési érték

Egy feladat, amely az időelteltet képviseli.

## Lásd még

* Typedef [TaskPtr](../../system/taskptr/)
* Osztály [CancellationToken](../../system.threading/cancellationtoken/)
* Névtér [System::Threading::Tasks](../)
* Könyvtár [Aspose.Slides](../../)