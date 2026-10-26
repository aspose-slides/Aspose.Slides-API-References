---
title: "System::Threading"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 1002
url: /sv/system.threading/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Händelse för att meddela väntande tråd som återställs automatiskt. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekaren och använd den pekaren för att skicka den till funktioner som argument. |
| [CancellationToken](./cancellationtoken/) | Sprider ett meddelande om att operationer bör avbrytas. Denna klass tillhandahåller en mekanism för kooperativ avbrytning mellan trådar, vilket gör att en tråd kan meddela andra att en operation ska avbrytas. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | Representerar en registrering för en avboknings-token återuppringning. |
| [CancellationTokenSource](./cancellationtokensource/) | En avboknings-token källa som kan användas för att utlösa avbokningsmeddelanden. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | Händelse som kan skickas till väntande tråd. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekaren och använd den pekaren för att skicka den till funktioner som argument. |
| [Interlocked](./interlocked/) | Tillhandahåller API för trådsäkra operationer. Detta är en statisk typ utan instansservice. Du bör aldrig skapa instanser av den på något sätt. |
| [ManualResetEvent](./manualresetevent/) | Händelse för att meddela väntande tråd som **inte** återställs automatiskt. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekaren och använd den pekaren för att skicka den till funktioner som argument. |
| [Monitor](./monitor/) | Klassen [Monitor](./monitor/) tillhandahåller en mekanism som synkroniserar åtkomst till objekt. |
| [Mutex](./mutex/) | [Mutex](./mutex/)-implementation. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekaren och använd den pekaren för att skicka den till funktioner som argument. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/)-implementation. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekaren och använd den pekaren för att skicka den till funktioner som argument. |
| [SynchronizationContext](./synchronizationcontext/) | Tillhandahåller grundfunktionaliteten för att sprida ett synkroniseringskontext över olika synkroniseringsoperationer. |
| [Thread](./thread/) | [Thread](./thread/)-implementation. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekaren och använd den pekaren för att skicka den till funktioner som argument. |
| [ThreadPool](./threadpool/) | [Thread](./thread/)-pool-API som tillåter att den skjuter jobb i kö som läses av en pool av arbets-trådar. Detta är en statisk typ utan instansservice. Du bör aldrig skapa instanser av den på något sätt. |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/)-pool intern data. Detta är en singleton-typ med minneshantering utförd av åtkomstfunktion(er). Du bör aldrig skapa instanser av den direkt. |
| [Timer](./timer/) | [Timer](./timer/)-klass som kör ett jobb-objekt i en separat tråd efter en fördröjning. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekaren och använd den pekaren för att skicka den till funktioner som argument. |
| [TimerQueue](./timerqueue/) | Kö som hanterar [Timer](./timer/)-objekt. Detta är bara en implementation. [Timer](./timer/)-objekt registrerar sig där själva, du behöver inte göra det för att använda dem – använd [Timer](./timer/)-klass-API istället. Detta är en singleton-typ med minneshantering utförd av åtkomstfunktion(er). Du bör aldrig skapa instanser av den direkt. |
| [WaitHandle](./waithandle/) | Väntande primitiv basklass. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekaren och använd den pekaren för att skicka den till funktioner som argument. |

## Strukturer

| Struktur | Beskrivning |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) tidsgräns speciella värden. Detta är en statisk typ utan instansservice. Du bör aldrig skapa instanser av den på något sätt. |

## Enummer

| Enum | Beskrivning |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Ställer in trådens apartment-tillstånd. |
| [EventResetMode](./eventresetmode/) | Indikerar hur händelsetillstånd återställs. |
| [ThreadState](./threadstate/) | Trådens tillstånd. |

## Typdefinitioner

| Typedef | Beskrivning |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/)-funktion med en parameter. |
| [ThreadStart](./threadstart/) | [Thread](./thread/)-funktion utan parametrar. |
| [WaitCallback](./waitcallback/) | Återuppringningsobjekt som ska köras när en plats finns. |
| [TimerCallback](./timercallback/) | Återuppringningsfunktion som ska anropas av timer. |
| [wait_handle_t](./wait_handle_t/) | Handtagstyp. |