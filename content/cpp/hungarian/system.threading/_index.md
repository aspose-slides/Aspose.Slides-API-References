---
title: "System::Threading"
second_title: Aspose.Slides C++ API referenciája
description: 
type: docs
weight: 1002
url: /hu/system.threading/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Esemény, amely értesíti a várakozó szálat, és automatikusan visszaállítja magát. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként. |
| [CancellationToken](./cancellationtoken/) | Értesítést terjeszt, hogy a műveleteket meg kell szakítani. Ez az osztály mechanizmust biztosít a szálak közötti együttműködő megszakításra, lehetővé téve, hogy egy szál értesítse a többit, hogy egy műveletet meg kell szakítani. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | Regisztrációt képvisel egy megszakítási token visszahíváshoz. |
| [CancellationTokenSource](./cancellationtokensource/) | Egy megszakítási token forrás, amely a megszakítási értesítések kiváltására használható. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | Esemény, amely elküldhető a várakozó szálnak. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként. |
| [Interlocked](./interlocked/) | API-t biztosít szálbiztos műveletekhez. Ez egy statikus típus, amely nem kínál példányszolgáltatásokat. Soha ne hozzon létre példányokat belőle semmilyen módon. |
| [ManualResetEvent](./manualresetevent/) | Esemény, amely értesíti a várakozó szálat, és nem áll vissza automatikusan. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként. |
| [Monitor](./monitor/) | A [Monitor](./monitor/) osztály mechanizmust biztosít az objektumokhoz való hozzáférés szinkronizálására. |
| [Mutex](./mutex/) | [Mutex](./mutex/) megvalósítás. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) megvalósítás. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként. |
| [SynchronizationContext](./synchronizationcontext/) | Alapvető funkcionalitást nyújt a szinkronizációs kontextus különböző szinkronizációs műveleteken átívelő terjesztéséhez. |
| [Thread](./thread/) | [Thread](./thread/) megvalósítás. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként. |
| [ThreadPool](./threadpool/) | [Thread](./thread/) pool API, amely lehetővé teszi feladatok sorba helyezését, amelyeket a munkavállaló szálak poolja olvas. Ez egy statikus típus, amely nem kínál példányszolgáltatásokat. Soha ne hozzon létre példányokat belőle semmilyen módon. |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/) pool belső adat. Ez egy singleton típus, amelynek memória-kezelése hozzáférési függvény(ek) által történik. Soha ne hozzon létre példányokat belőle közvetlenül. |
| [Timer](./timer/) | [Timer](./timer/) osztály, amely késleltetés után külön szálban hajtja végre a feladatot. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként. |
| [TimerQueue](./timerqueue/) | Sor, amely kezeli a [Timer](./timer/) objektumokat. Ez csak egy megvalósítás. A [Timer](./timer/) objektumok maguk regisztrálják magukat ott, nem kell ezt tennie a használatukhoz – helyette használja a [Timer](./timer/) osztály API-t. Ez egy singleton típus, amelynek memória-kezelése hozzáférési függvény(ek) által történik. Soha ne hozzon létre példányokat belőle közvetlenül. |
| [WaitHandle](./waithandle/) | Várakozási primitív alaposztály. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként. |
## Struktúrák

| Struktúra | Leírás |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) időtúllépés speciális értékek. Ez egy statikus típus, amely nem kínál példányszolgáltatásokat. Soha ne hozzon létre példányokat belőle semmilyen módon. |
## Enumerációk

| Enumeráció | Leírás |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Beállítja a szál apartman állapotát. |
| [EventResetMode](./eventresetmode/) | Jelzi, hogyan áll vissza az esemény állapota. |
| [ThreadState](./threadstate/) | A szál állapota. |
## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/) függvény egyetlen paraméterrel. |
| [ThreadStart](./threadstart/) | [Thread](./thread/) függvény paraméterek nélkül. |
| [WaitCallback](./waitcallback/) | Visszahívási elem, amely akkor kerül végrehajtásra, amikor van hely. |
| [TimerCallback](./timercallback/) | Visszahívási függvény, amelyet az időzítő hív meg. |
| [wait_handle_t](./wait_handle_t/) | Kezelő típus. |