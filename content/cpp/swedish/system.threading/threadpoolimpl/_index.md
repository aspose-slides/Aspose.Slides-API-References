---
title: ThreadPoolImpl
second_title: Aspose.Slides för C++ API-referens
description: Intern data för trådpool. Detta är en singleton-typ med minneshantering som görs via åtkomstfunktion(er). Du bör aldrig skapa instanser av den direkt.
type: docs
weight: 235
url: /sv/system.threading/threadpoolimpl/
---
## ThreadPoolImpl klass

[Thread](../thread/) pool interndata. Detta är en singleton-typ med minneshantering som sker via åtkomstfunktion(er). Du bör aldrig skapa instanser av den direkt.

```cpp
class ThreadPoolImpl
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Hämtar antalet tillgängliga trådar. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Hämtar initialiseringstillståndets singleton. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Hämtar maximalt antal samtidiga trådar. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Hämtar minimalt antal trådar som skapas av poolen. |
| void [JoinAll](./joinall/)() | Förenar alla ägda trådar. Väntar oändligt. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Lägger till arbetsobjekt i kö. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Ställer in antal trådar som ägs av poolen. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Ställer in minimalt antal trådar som ägs av poolen. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Konstruktor. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Destruktor. Förenar alla trådar om de ännu inte avslutats. |

## Se även

* Namnrymd [System::Threading](../)
* Bibliotek [Aspose.Slides](../../)