---
title: ThreadPoolImpl
second_title: Aspose.Slides voor C++ API-referentie
description: Thread pool interne gegevens. Dit is een singletontype met geheugenbeheer uitgevoerd door toegangsfunctie(s). U mag nooit direct instanties ervan maken.
type: docs
weight: 235
url: /nl/system.threading/threadpoolimpl/
---
## ThreadPoolImpl klasse

[Thread](../thread/) pool interne gegevens. Dit is een singletontype met geheugenbeheer uitgevoerd door toegangsfunctie(s). U mag nooit direct instanties ervan maken.

```cpp
class ThreadPoolImpl
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Haalt het aantal beschikbare threads op. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Haalt de initiële status van de singleton op. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Haalt het maximale aantal gelijktijdige threads op. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Haalt het minimale aantal threads op dat door de pool wordt aangemaakt. |
| void [JoinAll](./joinall/)() | Wacht op alle beheerde threads. Wacht oneindig. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Voegt een werkitem toe aan de wachtrij. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Stelt het aantal threads in dat eigendom is van de pool. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Stelt het minimale aantal threads in dat eigendom is van de pool. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Constructor. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Destructor. Wacht op alle threads als ze nog niet beëindigd waren. |

## Zie ook

* Naamruimte [System::Threading](../)
* Bibliotheek [Aspose.Slides](../../)