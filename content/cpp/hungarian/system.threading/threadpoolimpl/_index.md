---
title: ThreadPoolImpl
second_title: Aspose.Slides C++ API referencia
description: A szálkészlet belső adatai. Ez egy singleton típus, amelynek memóriakezelése a hozzáférési függvény(ek) által történik. Soha ne hozzon létre példányokat közvetlenül.
type: docs
weight: 235
url: /hu/system.threading/threadpoolimpl/
---
## ThreadPoolImpl osztály


[Thread](../thread/) pool internal data. Ez egy singleton típus, a memória kezelése a hozzáférési függvény(ek) által történik. Soha ne hozzon létre közvetlenül példányokat.

```cpp
class ThreadPoolImpl
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Lekéri az elérhető szálak számát. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Lekéri a kezdeti állapot singleton-ját. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Lekéri a párhuzamos szálak legnagyobb számát. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Lekéri a pool által létrehozott szálak legkisebb számát. |
| void [JoinAll](./joinall/)() | Csatlakozik minden tulajdonolt szálhoz. Végtelenül vár. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Munkadarabot ad a sorhoz. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Beállítja a pool által birtokolt szálak számát. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Beállítja a pool által birtokolt szálak minimális számát. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Konstruktor. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Destruktor. Csatlakozik az összes szálhoz, ha még nem lettek leállítva. |
## Lásd még

* Névtér [System::Threading](../)
* Könyvtár [Aspose.Slides](../../)