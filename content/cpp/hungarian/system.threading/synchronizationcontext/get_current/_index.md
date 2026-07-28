---
title: get_Current()
second_title: Aspose.Slides C++ API referencia
description: Lekéri az aktuális szál szinkronizációs kontextusát.
type: docs
weight: 40
url: /hu/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() metódus


Visszaadja a szinkronizációs kontextust az aktuális szálhoz.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```


### Return Value

SharedPtr<SynchronizationContext> a jelenlegi szál szinkronizációs kontextusára mutató megosztott pointer.
## Remarks



Null értéket ad vissza, ha az aktuális szálhoz nincs beállítva szinkronizációs kontextus. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [SynchronizationContext](../)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)