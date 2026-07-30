---
title: Details_WebException
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta l'eccezione generata da WebRequest quando si verifica un errore. Non creare mai istanze di questa classe manualmente. Usa invece la classe WebException. Non avvolgere mai le istanze della classe WebException in System::SmartPtr."
type: docs
weight: 92
url: /it/system.net/details_webexception/
---
## Details_WebException classe


Rappresenta l'eccezione che viene generata da [WebRequest](../webrequest/) quando si verifica un errore. Non creare mai istanze di questa classe manualmente. Utilizza invece la classe WebException. Non avvolgere mai le istanze della classe WebException in [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_WebException : public System::Details_InvalidOperationException
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [Exception](../../system/exception/) [CreateCompatibleException](./createcompatibleexception/)([Exception](../../system/exception/)) | Non è implementato. |
|  [Details_WebException](./details_webexception/)() | Costruisce una nuova istanza. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/)) | Costruisce una nuova istanza. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [Exception](../../system/exception/)) | Costruisce una nuova istanza. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [WebExceptionStatus](../webexceptionstatus/)) | Costruisce una nuova istanza. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [Exception](../../system/exception/), [WebExceptionStatus](../webexceptionstatus/), [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\>) | Costruisce una nuova istanza. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, compreso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, compreso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Restituisce un dizionario con i dati dell'eccezione personalizzata. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Restituisce un valore intero a 32 bit che è un codice HRESULT associato all'eccezione rappresentata dall'oggetto corrente. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Restituisce un riferimento all'oggetto che rappresenta l'eccezione interna. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Restituisce la stringa contenente la descrizione dell'errore. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [get_Response](./get_response/)() | Restituisce la risposta web con cui è associata l'eccezione corrente. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Restituisce la stringa contenente lo stack trace. |
| [WebExceptionStatus](../webexceptionstatus/) [get_Status](./get_status/)() | Restituisce il codice di stato. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Restituisce una copia dell'oggetto Exception che rappresenta l'eccezione più interna. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_invalidoperationexception/gettype/)() const override | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_invalidoperationexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso di un valore specificato. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Imposta HRESULT, un valore numerico codificato assegnato a una specifica eccezione. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un weak pointer (piuttosto che shared). Consente di cambiare i puntatori nei contenitori in modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Restituisce la rappresentazione stringa dell'oggetto corrente. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_invalidoperationexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implementa il metodo [what()](../../system/details_exception/what/) che è chiamato dalla classe [ExceptionWrapper](../../system/exceptionwrapper/). Nonostante il fatto che questa classe non erediti da std::exception, le classi derivate possono usare membri protetti/privati per implementare la loro logica. Spostare l'implementazione di questo metodo nel [ExceptionWrapper](../../system/exceptionwrapper/) potrebbe rompere quella logica. |
| virtual  [~Details_WebException](./~details_webexception/)() | Distrugge l'istanza corrente. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Details_InvalidOperationException](../../system/details_invalidoperationexception/)
* Spazio dei nomi [System::Net](../)
* Libreria [Aspose.Slides](../../)