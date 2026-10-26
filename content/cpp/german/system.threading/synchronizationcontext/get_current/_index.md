---
title: get_Current()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft den Synchronisationskontext für den aktuellen Thread ab.
type: docs
weight: 40
url: /de/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() Methode


Ruft den Synchronisationskontext für den aktuellen Thread ab.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```


### Rückgabewert

SharedPtr<SynchronizationContext> Ein SharedPtr zum Synchronisationskontext des aktuellen Threads.

## Bemerkungen


Gibt null zurück, wenn für den aktuellen Thread kein Synchronisationskontext festgelegt wurde. 

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [SynchronizationContext](../)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)