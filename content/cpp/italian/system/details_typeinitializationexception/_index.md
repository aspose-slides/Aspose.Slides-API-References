---
title: Details_TypeInitializationException
second_title: Riferimento API Aspose.Slides per C++
description: 
type: docs
weight: 742
url: /it/system/details_typeinitializationexception/
---
## Details_TypeInitializationException classe




```cpp
class Details_TypeInitializationException : public System::Details_SystemException
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Esegue un'emulazione del confronto a virgola mobile in stile C# in cui due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Esegue un'emulazione del confronto a virgola mobile in stile C# in cui due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Restituisce un dizionario con i dati dell'eccezione personalizzata. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Restituisce un valore intero a 32 bit che è un codice HRESULT associato all'eccezione rappresentata dall'oggetto corrente. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Restituisce un riferimento all'oggetto che rappresenta l'eccezione interna. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Restituisce la stringa contenente la descrizione dell'errore. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Restituisce la stringa contenente la traccia dello stack. |
| [String](../string/) [get_TypeName](./get_typename/)() |  |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Restituisce una copia dell'oggetto Exception che rappresenta l'eccezione più interna. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implementa l'istruzione lock() di C# per il blocco. Chiamare direttamente o usare l'oggetto sentry [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../object/object/)([Object](../object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Imposta HRESULT, un valore numerico codificato assegnato a una specifica eccezione. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento modello a un puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Restituisce la rappresentazione stringa dell'oggetto corrente. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Implementa lo sblocco dell'istruzione lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementa il metodo [what()](../details_exception/what/) che è chiamato dalla classe [ExceptionWrapper](../exceptionwrapper/). Nonostante il fatto che questa classe non erediti da std::exception, le classi derivate possono usare membri protetti/private per implementare la loro logica. Spostare l'implementazione di questo metodo nel [ExceptionWrapper](../exceptionwrapper/) potrebbe rompere tale logica. |
| virtual  [~Object](../object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Vedi anche

* Classe [Details_SystemException](../details_systemexception/)
* Namespace [System](../)
* Libreria [Aspose.Slides](../../)