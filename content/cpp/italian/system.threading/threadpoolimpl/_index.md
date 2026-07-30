---
title: ThreadPoolImpl
second_title: Riferimento API Aspose.Slides per C++
description: Dati interni del pool di thread. Si tratta di un tipo singleton con la gestione della memoria effettuata tramite funzione(i) di accesso. Non dovresti mai creare istanze di esso direttamente.
type: docs
weight: 235
url: /it/system.threading/threadpoolimpl/
---
## ThreadPoolImpl classe

[Thread](../thread/) dati interni del pool. Si tratta di un tipo singleton con la gestione della memoria effettuata tramite funzione(i) di accesso. Non dovresti mai creare istanze di esso direttamente.

```cpp
class ThreadPoolImpl
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Restituisce il numero di thread disponibili. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Restituisce lo stato di inizializzazione del singleton. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Restituisce il numero massimo di thread concorrenti. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Restituisce il numero minimo di thread creati dal pool. |
| void [JoinAll](./joinall/)() | Unisce tutti i thread posseduti. Attende indefinitamente. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Aggiunge un elemento di lavoro alla coda. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Imposta il numero di thread posseduti dal pool. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Imposta il numero minimo di thread posseduti dal pool. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Costruttore. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Distruttore. Unisce tutti i thread se non fossero ancora terminati. |
## Vedi anche

* Spazio dei nomi [System::Threading](../)
* Libreria [Aspose.Slides](../../)