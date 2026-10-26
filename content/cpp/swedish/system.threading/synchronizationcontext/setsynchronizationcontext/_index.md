---
title: SetSynchronizationContext()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in synkroniseringskontexten för den aktuella tråden.
type: docs
weight: 53
url: /sv/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) metod

Ställer in synkroniseringskontexten för den aktuella tråden.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | Synkroniseringskontexten som ska ställas in för den aktuella tråden. |
## Anmärkningar

Att skicka nullptr rensar synkroniseringskontexten för den aktuella tråden. 

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [SynchronizationContext](../)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)