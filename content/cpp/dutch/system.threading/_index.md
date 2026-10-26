---
title: "System::Threading"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 1002
url: /nl/system.threading/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Evenement om wachtende thread te informeren die automatisch reset. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze als argument door te geven aan functies. |
| [CancellationToken](./cancellationtoken/) | Propagereert een melding dat bewerkingen geannuleerd moeten worden. Deze klasse biedt een mechanisme voor coöperatieve annulering tussen threads, waardoor één thread anderen kan informeren dat een bewerking geannuleerd moet worden. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | Stelt een registratie voor een annulerings-token callback voor. |
| [CancellationTokenSource](./cancellationtokensource/) | Een annulerings-tokenbron die kan worden gebruikt om annuleringsmeldingen te activeren. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | Evenement dat kan worden verzonden naar een wachtende thread. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies als argument door te geven. |
| [Interlocked](./interlocked/) | Biedt API voor thread-veilige bewerkingen. Dit is een statisch type zonder instantie-services. Je mag nooit op welke manier dan ook instanties ervan maken. |
| [ManualResetEvent](./manualresetevent/) | Evenement om wachtende thread te informeren die niet automatisch reset. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze als argument door te geven aan functies. |
| [Monitor](./monitor/) | Klasse [Monitor](./monitor/) biedt een mechanisme dat de toegang tot objecten synchroniseert. |
| [Mutex](./mutex/) | [Mutex](./mutex/) implementatie. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies als argument door te geven. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) implementatie. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies als argument door te geven. |
| [SynchronizationContext](./synchronizationcontext/) | Biedt de basisfunctionaliteit voor het propaganderen van een synchronisatie-context over verschillende synchronisatie-operaties. |
| [Thread](./thread/) | [Thread](./thread/) implementatie. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies als argument door te geven. |
| [ThreadPool](./threadpool/) | [Thread](./thread/) pool-API die het mogelijk maakt taken in de wachtrij te plaatsen die gelezen worden door een pool van worker-threads. Dit is een statisch type zonder instantie-services. Je mag nooit op welke manier dan ook instanties ervan maken. |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/) pool interne gegevens. Dit is een singleton-type met geheugenbeheer uitgevoerd via toegang-functie(s). Je mag nooit direct instanties ervan maken. |
| [Timer](./timer/) | [Timer](./timer/) klasse die een taakitem na een vertraging in een afzonderlijke thread uitvoert. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies als argument door te geven. |
| [TimerQueue](./timerqueue/) | Wachtrij die [Timer](./timer/) objecten beheert. Dit is slechts een implementatie. [Timer](./timer/) objecten registreren zich zelf, je hoeft dit niet te doen om ze te gebruiken – gebruik in plaats daarvan de [Timer](./timer/) klasse-API. Dit is een singleton-type met geheugenbeheer uitgevoerd via toegang-functie(s). Je mag nooit direct instanties ervan maken. |
| [WaitHandle](./waithandle/) | Wacht-primitive basis-klasse. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies als argument door te geven. |

## Structuren

| Struct | Beschrijving |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) timeout speciale waarden. Dit is een statisch type zonder instantie-services. Je mag nooit op welke manier dan ook instanties ervan maken. |

## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Stelt de apartment-status van de thread in. |
| [EventResetMode](./eventresetmode/) | Geeft aan hoe de evenement-status wordt gereset. |
| [ThreadState](./threadstate/) | Status van de thread. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/) functie met één parameter. |
| [ThreadStart](./threadstart/) | [Thread](./thread/) functie zonder parameters. |
| [WaitCallback](./waitcallback/) | Callback-item dat wordt uitgevoerd zodra er een plek is. |
| [TimerCallback](./timercallback/) | Callback-functie die door een timer wordt aangeroepen. |
| [wait_handle_t](./wait_handle_t/) | Handle-type. |