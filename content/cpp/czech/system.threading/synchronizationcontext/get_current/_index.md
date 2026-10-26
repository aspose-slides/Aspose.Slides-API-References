---
title: get_Current()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá synchronizační kontext pro aktuální vlákno.
type: docs
weight: 40
url: /cs/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() metoda


Získá synchronizační kontext pro aktuální vlákno.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```


### Návratová hodnota

SharedPtr<SynchronizationContext> Sdílený ukazatel na synchronizační kontext aktuálního vlákna.
## Poznámky



Vrací null, pokud nebyl pro aktuální vlákno nastaven žádný synchronizační kontext. 

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [SynchronizationContext](../)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)