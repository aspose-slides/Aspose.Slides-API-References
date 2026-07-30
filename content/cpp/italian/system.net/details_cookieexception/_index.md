---
title: Details_CookieException
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un'eccezione sollevata quando la dimensione di CookieContainer è maggiore del valore della proprietà MaxCookieSize. Non creare mai istanze di questa classe manualmente. Utilizza invece la classe CookieException. Non inserire mai le istanze della classe CookieException in System::SmartPtr."
type: docs
weight: 79
url: /it/system.net/details_cookieexception/
---
## Details_CookieException classe


Rappresenta un'eccezione sollevata quando la dimensione di [CookieContainer](../cookiecontainer/) è maggiore del valore della proprietà MaxCookieSize. Non creare mai istanze di questa classe manualmente. Usa invece la classe CookieException. Non inserire mai le istanze della classe CookieException in [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_CookieException : public System::Details_FormatException
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [Details_CookieException](./details_cookieexception/)() | Costruisce una nuova istanza. |
|  [Details_CookieException](./details_cookieexception/)(std::nullptr_t) | Costruisce una nuova istanza. |
|  [Details_CookieException](./details_cookieexception/)([String](../../system/string/)) | Costruisce una nuova istanza. |
|  [Details_CookieException](./details_cookieexception/)([String](../../system/string/), [Exception](../../system/exception/)) | Costruisce una nuova istanza. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Restituisce un dizionario con i dati dell'eccezione personalizzata. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Restituisce un valore intero a 32 bit che è un codice HRESULT associato all'eccezione rappresentata dall'oggetto corrente. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Restituisce un riferimento all'oggetto che rappresenta l'eccezione interna. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Restituisce la stringa contenente la descrizione dell'errore. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Restituisce la stringa contenente la traccia dello stack. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Restituisce una copia dell'oggetto Exception che rappresenta l'eccezione più interna. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_formatexception/gettype/)() const override | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_formatexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione per copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione per copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Riduce il contatore di riferimenti condivisi del valore specificato. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Imposta HRESULT, un valore numerico codificato assegnato a una specifica eccezione. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento del modello come puntatore debole (invece che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Restituisce la rappresentazione stringa dell'oggetto corrente. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_formatexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implementa il metodo [what()](../../system/details_exception/what/) che è chiamato dalla classe [ExceptionWrapper](../../system/exceptionwrapper/). Nonostante il fatto che questa classe non erediti da std::exception, le classi derivate possono usare membri protetti/privati per implementare la loro logica. Spostare l'implementazione di questo metodo nel [ExceptionWrapper](../../system/exceptionwrapper/) potrebbe rompere tale logica. |
| virtual  [~Details_CookieException](./~details_cookieexception/)() | Distrugge l'istanza corrente. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Vedi anche

* Classe [Details_FormatException](../../system/details_formatexception/)
* Namespace [System::Net](../)
* Libreria [Aspose.Slides](../../)