---
title: get_Current()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de synchronisatiecontext op voor de huidige thread.
type: docs
weight: 40
url: /nl/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() methode


Haalt de synchronisatiecontext op voor de huidige thread.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```


### Retourwaarde

SharedPtr<SynchronizationContext> A shared pointer to the current thread's synchronization context.
## Opmerkingen



Retourneert null als er geen synchronisatiecontext is ingesteld voor de huidige thread. 

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SynchronizationContext](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)