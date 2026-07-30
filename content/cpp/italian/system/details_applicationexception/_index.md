---
title: Details_ApplicationException
second_title: Riferimento API Aspose.Slides per C++
description: "Una classe base per le classi che rappresentano eccezioni dell'applicazione (piuttosto che di sistema). Non creare mai istanze di questa classe manualmente. Usa invece la classe ApplicationException. Non avvolgere mai le istanze della classe ApplicationException in System::SmartPtr."
type: docs
weight: 313
url: /it/system/details_applicationexception/
---
## Details_ApplicationException classe


Una classe base per le classi che rappresentano eccezioni dell'applicazione (piuttosto che di sistema). Non creare mai istanze di questa classe manualmente. Usa invece la classe ApplicationException. Non avvolgere mai le istanze della classe ApplicationException in [System::SmartPtr](../smartptr/).

```cpp
class Details_ApplicationException : public System::Details_Exception
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Restituisce un dizionario con i dati dell'eccezione personalizzata. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Restituisce un valore intero a 32 bit che è un codice HRESULT associato all'eccezione rappresentata dall'oggetto corrente. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Restituisce un riferimento all'oggetto che rappresenta l'eccezione interna. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Restituisce la stringa contenente la descrizione dell'errore. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Restituisce la stringa contenente lo stack trace. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Restituisce una copia dell'oggetto Exception che rappresenta l'eccezione più interna. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../object/object/)([Object](../object/) const\&) | Costruttore di copia. In realtà non copia nulla, si limita a inizializzare un nuovo oggetto e a consentire la copia dei sottoclasse. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, si limita a inizializzare un nuovo oggetto e a consentire la copia dei sottoclasse. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Imposta HRESULT, un valore numerico codificato assegnato a una specifica eccezione. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un weak pointer (anziché shared). Consente di passare i puntatori nei contenitori alla modalità weak. |
| int [SharedCount](../object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Restituisce la rappresentazione stringa dell'oggetto corrente. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Implementa il blocco della dichiarazione C# lock() sbloccando. Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementa il metodo [what()](../details_exception/what/) che è chiamato dalla classe [ExceptionWrapper](../exceptionwrapper/). Nonostante il fatto che questa classe non erediti da std::exception, le classi derivate possono utilizzare membri protetti/privati per implementare la loro logica. Spostare l'implementazione di questo metodo nel [ExceptionWrapper](../exceptionwrapper/) potrebbe rompere tale logica. |
| virtual  [~Object](../object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Vedi anche

* Classe [Details_Exception](../details_exception/)
* Spazio dei nomi [System](../)
* Library [Aspose.Slides](../../)