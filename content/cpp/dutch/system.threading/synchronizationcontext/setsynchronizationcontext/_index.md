---
title: SetSynchronizationContext()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de synchronisatiecontext in voor de huidige thread.
type: docs
weight: 53
url: /nl/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) method


Stelt de synchronisatiecontext in voor de huidige thread.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | De synchronisatiecontext die voor de huidige thread moet worden ingesteld. |
## Opmerkingen



Het doorgeven van nullptr zal de synchronisatiecontext voor de huidige thread wissen. 

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [SynchronizationContext](../)
* Naamruimte [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)