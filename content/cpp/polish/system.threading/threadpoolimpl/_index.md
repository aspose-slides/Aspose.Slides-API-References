---
title: ThreadPoolImpl
second_title: Odnośnik API Aspose.Slides dla C++
description: Wewnętrzne dane puli wątków. To jest typ singleton z zarządzaniem pamięcią realizowanym przez funkcje dostępowe. Nigdy nie powinieneś tworzyć jego instancji bezpośrednio.
type: docs
weight: 235
url: /pl/system.threading/threadpoolimpl/
---
## ThreadPoolImpl klasa

[Thread](../thread/) wewnętrzne dane puli. To jest typ singleton z zarządzaniem pamięcią realizowanym przez funkcje dostępowe. Nigdy nie powinieneś tworzyć jego instancji bezpośrednio.

```cpp
class ThreadPoolImpl
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Zwraca liczbę dostępnych wątków. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Zwraca stan inicjalizacji singletona. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Zwraca maksymalną liczbę jednoczesnych wątków. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Zwraca minimalną liczbę wątków tworzonych przez pulę. |
| void [JoinAll](./joinall/)() | Łączy wszystkie posiadane wątki. Czeka w nieskończoność. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Dodaje element pracy do kolejki. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Ustawia liczbę wątków posiadanych przez pulę. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Ustawia minimalną liczbę wątków posiadanych przez pulę. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Konstruktor. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Destruktor. Łączy wszystkie wątki, jeśli nie zostały jeszcze zakończone. |

## Zobacz także

* Przestrzeń nazw [System::Threading](../)
* Biblioteka [Aspose.Slides](../../)