---
title: AsTask()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja ezt a ResultValueTask-et egy megosztott mutatóra a ResultTask<T> típushoz.
type: docs
weight: 79
url: /hu/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const metódus

Átalakítja ezt a [ResultValueTask](../)-t egy megosztott mutatóra a ResultTask<T> típusú objektumhoz.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```

### Visszatérési érték

RTaskPtr<T> Egy megosztott mutató a ResultTask<T>-re, amely ezt a műveletet képviseli.

## Megjegyzések

Ha a [ResultValueTask](../) közvetlen eredményt tartalmaz, létrehoz egy befejezett feladatot azzal az eredménnyel. Ha egy feladatot tartalmaz, egy megosztott mutatót ad vissza arra a feladatra. 

## Lásd még

* Típusdefiníció [RTaskPtr](../../../system/rtaskptr/)
* Osztály [ResultValueTask](../)
* Névtér [System::Threading::Tasks](../../)
* Könyvtár [Aspose.Slides](../../../)