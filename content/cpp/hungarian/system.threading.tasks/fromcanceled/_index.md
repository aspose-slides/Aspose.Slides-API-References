---
title: FromCanceled()
second_title: Aspose.Slides C++-hoz API referencia
description: Létrehoz egy feladatot, amely a megadott token miatt a leállítás következtében befejeződött.
type: docs
weight: 118
url: /hu/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled(const CancellationToken\&) függvény

Létrehoz egy feladatot, amely a megadott token miatt a leállítás következtében befejeződött.

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | A leállítási token, amely a feladat leállítását okozta. |

### Visszatérési érték

Egy leállított feladat.

## Lásd még

* Típusdefiníció [TaskPtr](../../system/taskptr/)
* Osztály [CancellationToken](../../system.threading/cancellationtoken/)
* Névtér [System::Threading::Tasks](../)
* Könyvtár [Aspose.Slides](../../)