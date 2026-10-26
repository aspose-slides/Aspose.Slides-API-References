---
title: SetSynchronizationContext()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt den Synchronisationskontext für den aktuellen Thread.
type: docs
weight: 53
url: /de/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) Methode

Setzt den Synchronisationskontext für den aktuellen Thread.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | Der Synchronisationskontext, der für den aktuellen Thread festgelegt werden soll. |
## Anmerkungen

Durch Übergeben von nullptr wird der Synchronisationskontext für den aktuellen Thread gelöscht.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [SynchronizationContext](../)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)