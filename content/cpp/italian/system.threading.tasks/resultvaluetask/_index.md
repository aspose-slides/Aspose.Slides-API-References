---
title: ResultValueTask
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta un tipo ibrido simile a un task che può avvolgere sia un valore di risultato diretto sia un ResultTask<T>.
type: docs
weight: 53
url: /it/system.threading.tasks/resultvaluetask/
---
## ResultValueTask classe

Rappresenta un tipo ibrido simile a un task che può avvolgere sia un valore di risultato diretto sia un ResultTask<T>.

```cpp
template<typename T>class ResultValueTask : public System::IEquatable<ResultValueTask<T>>,
                                            public System::Details::BoxableObjectBase
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | The type of the result produced by the task. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [RTaskPtr](../../system/rtaskptr/)\<T\> [AsTask](./astask/)() const | Converte questo [ResultValueTask](./) in un puntatore condiviso a ResultTask<T>. |
| [Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable](../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Configura un awaiter per questo task. |
| **bool** [Equals](./equals/)([ResultValueTask](./)) override | Determina se questa istanza è uguale a un'altra istanza di [ResultValueTask](./). |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determina se questa istanza è uguale a un altro oggetto. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | Determina se gli oggetti corrente e specificato sono uguali. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per usi interni. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | Restituisce un valore che indica se il task è terminato a causa di una cancellazione. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | Restituisce un valore che indica se il task è completato. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Restituisce un valore che indica se il task è terminato con successo. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | Restituisce un valore che indica se il task è terminato a causa di un'eccezione non gestita. |
| T [get_Result](./get_result/)() | Restituisce il risultato del task completato. |
| [Runtime::CompilerServices::ResultValueTaskAwaiter](../../system.runtime.compilerservices/resultvaluetaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Restituisce un awaiter per questo task per supportare le espressioni await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Restituisce la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Restituisce il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita il clonaggio di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| **bool** [operator!=](./operator_not_equal/)(const [ResultValueTask](./)\&) const | Operatore di diseguaglianza per [ResultValueTask](./). |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| **bool** [operator==](./operator_equal_equal/)(const [ResultValueTask](./)\&) const | Operatore di uguaglianza per [ResultValueTask](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso di un valore specificato. |
|  [ResultValueTask](./resultvaluetask/)() | Costruisce un [ResultValueTask](./) vuoto e non inizializzato. |
|  [ResultValueTask](./resultvaluetask/)(const T\&) | Costruisce un [ResultValueTask](./) completato con il risultato specificato. |
|  [ResultValueTask](./resultvaluetask/)(const [RTaskPtr](../../system/rtaskptr/)\<T\>\&) | Costruisce un [ResultValueTask](./) da un puntatore condiviso a ResultTask<T>. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (invece che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Restituisce il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del statement lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Osservazioni

[ResultValueTask](./) combina i vantaggi di [ValueTask](../valuetask/) (allocazioni ridotte per risultati sincroni) con la capacità di avvolgere oggetti ResultTask<T> esistenti. Fornisce un'interfaccia awaitable e vari metodi di ispezione dello stato del task. 
## Vedi anche

* Classe [IEquatable](../../system/iequatable/)
* Spazio dei nomi [System::Threading::Tasks](../)
* Libreria [Aspose.Slides](../../)