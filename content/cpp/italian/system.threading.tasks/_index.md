---
title: "System::Threading::Tasks"
second_title: Riferimento API Aspose.Slides per C++
description: 
type: docs
weight: 1015
url: /it/system.threading.tasks/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [Parallel](./parallel/) | Fornisce supporto per loop e regioni parallele. |
| [ParallelLoopResult](./parallelloopresult/) | Fornisce lo stato di completamento di un loop [Parallel](./parallel/). |
| [ParallelOptions](./paralleloptions/) | Memorizza le opzioni che configurano l'operazione dei metodi sulla classe [Parallel](./parallel/). |
| [ResultTask](./resulttask/) | Una specializzazione [Task](./task/) che restituisce un valore di risultato al completamento. |
| [ResultValueTask](./resultvaluetask/) | Rappresenta un tipo ibrido simile a un task che può avvolgere sia un valore di risultato diretto sia un ResultTask<T>. |
| [Task](./task/) | Rappresenta un'operazione asincrona che può essere attesa e composta con altri task. |
| [TaskScheduler](./taskscheduler/) | Rappresenta un oggetto che gestisce il lavoro a basso livello di accodare task sui thread. |
| [ValueTask](./valuetask/) | Fornisce un risultato attendibile di un'operazione asincrona. |
## Funzioni

| Funzione | Descrizione |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Crea un task che si completa dopo un ritardo temporale. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Crea un task che si completa dopo un ritardo temporale e può essere annullato. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Crea un task che è stato completato a causa di annullamento con il token specificato. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Crea un task che è stato completato con un'eccezione specificata. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Crea un task che è stato completato con un'eccezione e un tipo di risultato specificati. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Crea un task che è stato completato con successo con il risultato specificato. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Accoda il lavoro specificato per l'esecuzione nel thread pool e restituisce un handle [Task](./task/) per quel lavoro. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Accoda il lavoro specificato per l'esecuzione nel thread pool e restituisce un handle [Task](./task/) per quel lavoro. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Accoda il lavoro specificato per l'esecuzione nel thread pool e restituisce un proxy per il [Task](./task/) restituito dalla funzione. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Accoda il lavoro specificato per l'esecuzione nel thread pool e restituisce un handle Task<TResult> per quel lavoro. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Attende che tutti gli oggetti [Task](./task/) forniti completino l'esecuzione. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Attende che tutti gli oggetti [Task](./task/) forniti completino l'esecuzione. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Attende che uno qualsiasi degli oggetti [Task](./task/) forniti completi l'esecuzione. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Attende che uno qualsiasi degli oggetti [Task](./task/) forniti completi l'esecuzione. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Crea un task che si completerà quando tutti i task forniti saranno completati. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Crea un task che si completerà quando tutti i task forniti saranno completati. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Crea un task che si completerà quando tutti i task forniti saranno completati. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Crea un task che si completerà quando tutti i task forniti saranno completati. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Crea un task che si completerà quando uno qualsiasi dei task forniti sarà completato. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Crea un task che si completerà quando uno qualsiasi dei task forniti sarà completato. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Crea un task che si completerà quando uno qualsiasi dei task forniti sarà completato. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Crea un task che si completerà quando uno qualsiasi dei task forniti sarà completato. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Crea un task attendibile che restituisce in modo asincrono al contesto corrente quando viene atteso. |
## Enumerazioni

| Enumerazione | Descrizione |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |