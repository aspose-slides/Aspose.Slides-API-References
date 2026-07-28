---
title: SetSynchronizationContext()
second_title: Aspose.Slides C++ API Referencia
description: Beállítja a szinkronizációs kontextust az aktuális szálhoz.
type: docs
weight: 53
url: /hu/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) metódus

Beállítja a szinkronizációs kontextust az aktuális szálhoz.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | A szinkronizációs kontextus, amelyet az aktuális szálhoz kell beállítani. |
## Megjegyzések

A nullptr átadása törli a szinkronizációs kontextust az aktuális szálról. 

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [SynchronizationContext](../)
* Névterület [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)