---
title: "System::Threading"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 1002
url: /it/system.threading/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Evento per notificare il thread in attesa che si resetta automaticamente. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizzare tale puntatore per passarlo alle funzioni come argomento. |
| [CancellationToken](./cancellationtoken/) | Propaga una notifica che le operazioni devono essere annullate. Questa classe fornisce un meccanismo per la cancellazione cooperativa tra thread, consentendo a un thread di notificare gli altri che un'operazione deve essere annullata. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | Rappresenta una registrazione per una callback di token di cancellazione. |
| [CancellationTokenSource](./cancellationtokensource/) | Una sorgente di token di cancellazione che può essere usata per attivare notifiche di cancellazione. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | Evento che può essere inviato al thread in attesa. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizzare tale puntatore per passarlo alle funzioni come argomento. |
| [Interlocked](./interlocked/) | Fornisce API per operazioni thread-safe. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo. |
| [ManualResetEvent](./manualresetevent/) | Evento per notificare il thread in attesa che non si resetta automaticamente. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizzare tale puntatore per passarlo alle funzioni come argomento. |
| [Monitor](./monitor/) | La classe [Monitor](./monitor/) fornisce un meccanismo che sincronizza l'accesso agli oggetti. |
| [Mutex](./mutex/) | [Mutex](./mutex/) implementazione. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizzare tale puntatore per passarlo alle funzioni come argomento. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) implementazione. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizzare tale puntatore per passarlo alle funzioni come argomento. |
| [SynchronizationContext](./synchronizationcontext/) | Fornisce la funzionalità di base per propagare un contesto di sincronizzazione attraverso varie operazioni di sincronizzazione. |
| [Thread](./thread/) | [Thread](./thread/) implementazione. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizzare tale puntatore per passarlo alle funzioni come argomento. |
| [ThreadPool](./threadpool/) | [Thread](./thread/) pool API che consente di inserire lavori nella coda da leggere da un pool di thread worker. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo. |
| [ThreadPoolImpl](./threadpoolimpl/) | Dati interni del pool [Thread](./thread/). Questo è un tipo singleton con gestione della memoria eseguita tramite funzione(i) di accesso. Non dovresti mai creare istanze di esso direttamente. |
| [Timer](./timer/) | Classe [Timer](./timer/) che esegue un elemento di lavoro in un thread separato dopo un ritardo. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizzare tale puntatore per passarlo alle funzioni come argomento. |
| [TimerQueue](./timerqueue/) | Coda che gestisce oggetti [Timer](./timer/). Questa è solo un'implementazione. Gli oggetti [Timer](./timer/) si registrano lì da soli, non è necessario farlo per usarli – usa invece l'API della classe [Timer](./timer/). Questo è un tipo singleton con gestione della memoria eseguita tramite funzione(i) di accesso. Non dovresti mai creare istanze di esso direttamente. |
| [WaitHandle](./waithandle/) | Classe base primitiva di attesa. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizzare tale puntatore per passarlo alle funzioni come argomento. |

## Strutture

| Struttura | Descrizione |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) valori speciali di timeout. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo. |

## Enums

| Enum | Descrizione |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Imposta lo stato di appartenenza del thread. |
| [EventResetMode](./eventresetmode/) | Indica come lo stato dell'evento si resetta. |
| [ThreadState](./threadstate/) | Stato del thread. |

## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/) funzione con un singolo parametro. |
| [ThreadStart](./threadstart/) | [Thread](./thread/) funzione senza parametri. |
| [WaitCallback](./waitcallback/) | Elemento di callback da eseguire una volta disponibile uno slot. |
| [TimerCallback](./timercallback/) | Funzione di callback da chiamare dal timer. |
| [wait_handle_t](./wait_handle_t/) | Tipo handle. |