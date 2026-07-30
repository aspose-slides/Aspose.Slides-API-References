---
title: SetSynchronizationContext()
second_title: Aspose.Slides pro C++ – reference API
description: Nastaví synchronizační kontext pro aktuální vlákno.
type: docs
weight: 53
url: /cs/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) metoda

Nastaví synchronizační kontext pro aktuální vlákno.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | Synchronizační kontext, který se má nastavit pro aktuální vlákno. |
## Poznámky

Předání nullptr vymaže synchronizační kontext pro aktuální vlákno.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [SynchronizationContext](../)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)