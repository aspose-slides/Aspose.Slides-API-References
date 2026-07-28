---
title: EventHandler
second_title: Aspose.Slides C++ API referencia
description: "Egy olyan metódust reprezentál, amely reagál egy eseményre, és azt feldolgozza. Ennek a típusnak a veremben kell elhelyezkednie, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusú objektumok kezelésére."
type: docs
weight: 3706
url: /hu/system/eventhandler/
---
## EventHandler típusdefiníció


Egy olyan módszert képvisel, amely reagál egy eseményre, és azt feldolgozza. Ez a típusnak a veremben kell lennie, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusú objektumok kezelésére.

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```


## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)