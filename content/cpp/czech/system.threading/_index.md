---
title: "System::Threading"
second_title: Aspose.Slides pro C++ API Reference
description: 
type: docs
weight: 1002
url: /cs/system.threading/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Událost, která upozorní čekající vlákno a resetuje se automaticky. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [CancellationToken](./cancellationtoken/) | Šíří oznámení, že operace mají být zrušeny. Tato třída poskytuje mechanismus pro kooperativní zrušení mezi vlákny, umožňující jednomu vláknu upozornit ostatní, že operace má být zrušena. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | Reprezentuje registraci pro zpětné volání tokenu zrušení. |
| [CancellationTokenSource](./cancellationtokensource/) | Zdroj tokenu zrušení, který lze použít k vyvolání oznámení o zrušení. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | Událost, kterou lze poslat čekajícímu vláknu. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [Interlocked](./interlocked/) | Poskytuje API pro operace zabezpečené pro vlákna. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance žádným způsobem. |
| [ManualResetEvent](./manualresetevent/) | Událost, která upozorní čekající vlákno a neresetuje se automaticky. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [Monitor](./monitor/) | Třída [Monitor](./monitor/) poskytuje mechanismus, který synchronizuje přístup k objektům. |
| [Mutex](./mutex/) | Implementace [Mutex](./mutex/). Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [Semaphore](./semaphore/) | Implementace [Semaphore](./semaphore/). Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [SynchronizationContext](./synchronizationcontext/) | Poskytuje základní funkčnost pro šíření synchronizačního kontextu napříč různými synchronizačními operacemi. |
| [Thread](./thread/) | Implementace [Thread](./thread/). Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [ThreadPool](./threadpool/) | API fondu [Thread](./thread/) umožňující vkládání úloh do fronty, kterou čtou vlákna pracovníků. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance žádným způsobem. |
| [ThreadPoolImpl](./threadpoolimpl/) | Interní data fondu [Thread](./thread/). Jedná se o typ singleton s řízením paměti prováděným přístupovými funkcemi. Nikdy byste neměli vytvářet jeho instance přímo. |
| [Timer](./timer/) | Třída [Timer](./timer/) provádějící úlohu ve zvláštním vlákně po zpoždění. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [TimerQueue](./timerqueue/) | Fronta, která zpracovává objekty [Timer](./timer/). Jedná se pouze o implementaci. Objekty [Timer](./timer/) se registrují samy; není nutné je registrovat pro jejich použití – místo toho použijte API třídy [Timer](./timer/). Jedná se o typ singleton s řízením paměti prováděným přístupovými funkcemi. Nikdy byste neměli vytvářet jeho instance přímo. |
| [WaitHandle](./waithandle/) | Základní třída čekacího primitivu. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
## Struktury

| Struktura | Popis |
| --- | --- |
| [Timeout](./timeout/) | Speciální hodnoty časového limitu [Threading](./). Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance žádným způsobem. |
## Výčty

| Výčet | Popis |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Nastavuje stav apartmantu vlákna. |
| [EventResetMode](./eventresetmode/) | Určuje, jak se stav události resetuje. |
| [ThreadState](./threadstate/) | Stav vlákna. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | Funkce [Thread](./thread/) s jedním parametrem. |
| [ThreadStart](./threadstart/) | Funkce [Thread](./thread/) bez parametrů. |
| [WaitCallback](./waitcallback/) | Položka zpětného volání, která bude vykonána, jakmile bude místo. |
| [TimerCallback](./timercallback/) | Funkce zpětného volání, která bude volána časovačem. |
| [wait_handle_t](./wait_handle_t/) | Typ handle. |