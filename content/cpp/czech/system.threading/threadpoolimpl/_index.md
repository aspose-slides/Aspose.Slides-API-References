---
title: ThreadPoolImpl
second_title: Aspose.Slides pro C++ referenční příručka API
description: Interní data fondu vláken. Jedná se o typ singletonu, jehož správa paměti je prováděna pomocí přístupových funkcí. Neměli byste nikdy vytvářet jeho instance přímo.
type: docs
weight: 235
url: /cs/system.threading/threadpoolimpl/
---
## ThreadPoolImpl třída


[Thread](../thread/) interní data fondu. Jedná se o typ singletonu, jehož správa paměti je prováděna pomocí přístupových funkcí. Neměli byste vytvářet jeho instance přímo.

```cpp
class ThreadPoolImpl
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Získá počet dostupných vláken. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Získá singleton stav inicializace. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Získá maximální počet souběžných vláken. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Získá minimální počet vláken vytvářených poolem. |
| void [JoinAll](./joinall/)() | Spojí všechna vlastněná vlákna. Čeká nekonečně. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Přidá položku úlohy do fronty. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Nastaví počet vláken vlastněných poolem. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Nastaví minimální počet vláken vlastněných poolem. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Konstruktor. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Destruktor. Připojí všechna vlákna, pokud ještě nebyla ukončena. |
## Viz také

* Jmenný prostor [System::Threading](../)
* Knihovna [Aspose.Slides](../../)