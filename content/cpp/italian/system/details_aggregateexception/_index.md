---
title: Details_AggregateException
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta un'eccezione che contiene più eccezioni interne.
type: docs
weight: 300
url: /it/system/details_aggregateexception/
---
## Details_AggregateException classe

Rappresenta un'eccezione che contiene più eccezioni interne.

```cpp
class Details_AggregateException : public System::Details_Exception
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [AggregateException](../aggregateexception/) [Flatten](./flatten/)() | Appiattisce l'eccezione aggregata estraendo tutte le AggregateExceptions annidate in un elenco a un unico livello. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Restituisce un dizionario con dati di eccezione personalizzati. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Restituisce un valore intero a 32 bit che è il codice HRESULT associato all'eccezione rappresentata dall'oggetto corrente. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Restituisce un riferimento all'oggetto che rappresenta l'eccezione interna. |
| **int32_t** [get_InnerExceptionCount](./get_innerexceptioncount/)() | Ottiene il numero di eccezioni interne contenute in questa eccezione aggregata. |
| [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[Exception](../exception/)\>\> [get_InnerExceptions](./get_innerexceptions/)() | Ottiene una raccolta di sola lettura delle eccezioni interne. |
| const [ArrayPtr](../arrayptr/)\<[Exception](../exception/)\>\& [get_InternalInnerExceptions](./get_internalinnerexceptions/)() | Restituisce l'array interno delle eccezioni interne. |
| [String](../string/) [get_Message](./get_message/)() const override | Sovrascrive il messaggio di base per includere informazioni aggregate da tutte le eccezioni interne. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Restituisce la stringa contenente lo stack trace. |
| [Exception](../exception/) [GetBaseException](./getbaseexception/)() const override | Restituisce l'eccezione causa radice decompattando ricorsivamente le eccezioni interne. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../object/gettype/). |
| void [Handle](./handle/)(const [Func](../func/)\<[Exception](../exception/), **bool**\>\&) | Invoca una funzione gestore su ciascuna eccezione interna e rilancia eventuali eccezioni non gestite. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../object/object/)([Object](../object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie di sottoclassi. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie di sottoclassi. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Imposta HRESULT, un valore numerico codificato che è assegnato a una specifica eccezione. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un weak pointer (piuttosto che shared). Consente di cambiare i puntatori nei contenitori in modalità weak. |
| int [SharedCount](../object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa dell'eccezione, includendo tutte le eccezioni interne. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa la costruzione C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa il contatore di riferimenti weak. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa il contatore di riferimenti weak. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementa il metodo [what()](../details_exception/what/) che è chiamato dalla classe [ExceptionWrapper](../exceptionwrapper/). Nonostante il fatto che questa classe non erediti da std::exception, le classi derivate possono usare membri protetti/privati per implementare la loro logica. Spostare l'implementazione di questo metodo al [ExceptionWrapper](../exceptionwrapper/) potrebbe rompere quella logica. |
| virtual  [~Object](../object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Osservazioni

Questa classe è tipicamente usata per raggruppare diverse eccezioni che si verificano contemporaneamente, ad esempio in scenari di elaborazione parallela o di esecuzione di attività asincrone. Consente agli utenti di esaminare, appiattire o gestire selettivamente le eccezioni contenute.

## Vedi anche

* Classe [Details_Exception](../details_exception/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)