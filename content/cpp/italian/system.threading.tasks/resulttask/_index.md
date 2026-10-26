---
title: ResultTask
second_title: Riferimento API di Aspose.Slides per C++
description: Una specializzazione di Task che restituisce un valore di risultato al completamento.
type: docs
weight: 40
url: /it/system.threading.tasks/resulttask/
---
## ResultTask classe


Una specializzazione [Task](../task/) che restituisce un valore di risultato al completamento.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo del valore di risultato restituito dall'operazione |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [Activate](../task/activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Attiva l'operazione per l'esecuzione su un pianificatore. |
| void [AddCompletionAction](../task/addcompletionaction/)(const [Action](../../system/action/)<>\&) | Aggiunge un'azione di continuazione da eseguire al completamento. |
| void [Cancel](../task/cancel/)() | Segna l'operazione come annullata e termina l'operazione. |
| void [Complete](./complete/)(const T\&) | Imposta il valore di risultato per l'operazione e la completa. |
| void [Complete](../task/complete/)() | Segna l'operazione come completata e la termina. |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Configura come le attese su questa operazione con risultato devono comportarsi riguardo alla cattura del contesto. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | Crea una continuazione che viene eseguita quando l'operazione con risultato si completa. |
| [RTaskPtr](../../system/rtaskptr/)\<TNewResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>, TNewResult\>\&) | Crea una continuazione che viene eseguita quando l'operazione con risultato si completa. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Crea una continuazione che viene eseguita quando l'operazione si completa. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Crea una continuazione che viene eseguita quando l'operazione si completa. |
| void [Deactivate](../task/deactivate/)() | Disattiva l'operazione per l'esecuzione sul suo pianificatore corrente, se presente. |
| void [Dispose](../task/dispose/)() override | Rilascia le risorse associate all'operazione. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| void [Execute](../task/execute/)() | Esegue la funzione dell'operazione. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | Ottiene l'oggetto di stato definito dall'utente associato all'operazione. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | Ottiene un'operazione completata (singleton). |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](../task/get_exception/)() const | Ottiene l'ID per l'operazione. |
| **int32_t** [get_Id](../task/get_id/)() const |  |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | Restituisce se l'operazione è stata completata a causa di una cancellazione. |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | Restituisce se l'operazione è stata completata. |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | Restituisce se l'operazione è stata completata a causa di un'eccezione non gestita. |
| T [get_Result](./get_result/)() | Ottiene il risultato dell'operazione asincrona. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](../task/get_scheduler/)() const | Ottiene il pianificatore associato a questa operazione. |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | Ottiene lo stato corrente dell'operazione. |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Ottiene un awaiter per questa operazione con risultato da utilizzare con Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco di lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, davvero, inizializza solo un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, davvero, inizializza solo un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | Crea un [ResultTask](./) con una funzione che restituisce un valore. |
|  [ResultTask](./resulttask/)() | Implementazione interna. Non per il codice utente. |
|  [ResultTask](./resulttask/)(const T\&) | Costruttore interno per creare operazioni con risultato con il risultato specificato. |
| void [RunSynchronously](../task/runsynchronously/)() | Esegue l'operazione in modo sincrono sul thread corrente. |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Esegue l'operazione in modo sincrono usando il pianificatore specificato. |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | Imposta la funzione interna da eseguire. |
| void [set_Result](./set_result/)(const T\&) | Imposta il valore di risultato per l'operazione. |
| void [set_Scheduler](../task/set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Imposta il pianificatore associato a questa operazione. |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | Imposta lo stato dell'operazione. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n'th argomento template a un puntatore debole (piuttosto che condiviso). Consente lo scambio dei puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [Start](../task/start/)() | Avvia l'esecuzione dell'operazione usando il pianificatore predefinito. |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Avvia l'esecuzione dell'operazione usando il pianificatore specificato. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | Crea un [Task](../task/) con un'azione da eseguire. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Crea un [Task](../task/) con un'azione e un token di cancellazione. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Crea un [Task](../task/) con un'azione con stato e un oggetto di stato. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Crea un [Task](../task/) con un'azione con stato, stato e token di cancellazione. |
|  [Task](../task/task/)() | Costruttore interno per creare operazioni non inizializzate. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Attende il completamento dell'operazione con supporto alla cancellazione. |
| void [Wait](../task/wait/)() | Attende il completamento dell'operazione. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
|  [~Task](../task/~task/)() | Distruttore. |
## Osservazioni



Rappresenta un'operazione asincrona che produce un risultato, simile a System.Threading.Tasks.Task<TResult> in .NET 
## Vedi anche

* Classe [Task](../task/)
* Namespace [System::Threading::Tasks](../)
* Libreria [Aspose.Slides](../../)