---
title: get_Current()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar synkroniseringskontexten för den aktuella tråden.
type: docs
weight: 40
url: /sv/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() metod


Hämtar synkroniseringskontexten för den aktuella tråden.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```


### Returvärde

SharedPtr<SynchronizationContext> En delad pekare till den aktuella trådens synkroniseringskontext.
## Anmärkningar



Returnerar null om ingen synkroniseringskontext har ställts in för den aktuella tråden. 

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [SynchronizationContext](../)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)