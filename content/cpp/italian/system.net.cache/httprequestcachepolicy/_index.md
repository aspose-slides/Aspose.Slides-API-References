---
title: HttpRequestCachePolicy
second_title: Riferimento API Aspose.Slides per C++
description: "Politica di cache HTTP che esprime la semantica di caching HTTP RFC2616. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò può generare errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e usare tale puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 1
url: /it/system.net.cache/httprequestcachepolicy/
---
## classe HttpRequestCachePolicy

HTTP cache policy that expresses RFC2616 HTTP caching semantic Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpRequestCachePolicy : public System::Net::Cache::RequestCachePolicy
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di floating point in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di floating point in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [DateTime](../../system/datetime/) [get_CacheSyncDate](./get_cachesyncdate/)() const | Restituisce il momento in cui le risorse memorizzate nella cache devono essere ri-convalidate. |
| [DateTime](../../system/datetime/) [get_InternalCacheSyncDateUtc](./get_internalcachesyncdateutc/)() const | Restituisce l'ora in formato UTC in cui le risorse memorizzate nella cache devono essere ri-convalidate. Solo per uso interno. |
| [HttpRequestCacheLevel](../httprequestcachelevel/) [get_Level](./get_level/)() const | Restituisce il valore HttpRequestCacheLevel specificato. |
| [RequestCacheLevel](../requestcachelevel/) [get_Level](../requestcachepolicy/get_level/)() | Restituisce il valore RequestCacheLevel specificato. |
| [TimeSpan](../../system/timespan/) [get_MaxAge](./get_maxage/)() const | Restituisce l'età massima consentita per una risorsa. |
| [TimeSpan](../../system/timespan/) [get_MaxStale](./get_maxstale/)() const | Restituisce il valore massimo di obsolescenza consentito per una risorsa. |
| [TimeSpan](../../system/timespan/) [get_MinFresh](./get_minfresh/)() const | Restituisce l'età minima consentita per una risorsa. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Restituisce la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Restituisce il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)() | Costruisce una nuova istanza. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpRequestCacheLevel](../httprequestcachelevel/)) | Costruisce una nuova istanza. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/)) | Costruisce una nuova istanza. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/), [TimeSpan](../../system/timespan/)) | Costruisce una nuova istanza. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)([DateTime](../../system/datetime/)) | Costruisce una nuova istanza. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/), [TimeSpan](../../system/timespan/), [DateTime](../../system/datetime/)) | Costruisce una nuova istanza. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e abilita la costruzione di copia nelle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e abilita la costruzione di copia nelle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| [RequestCachePolicy](../requestcachepolicy/requestcachepolicy/)() | Costruisce una nuova istanza. |
| [RequestCachePolicy](../requestcachepolicy/requestcachepolicy/)([RequestCacheLevel](../requestcachelevel/)) | Costruisce una nuova istanza con il valore RequestCacheLevel specificato. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore weak (piuttosto che shared). Consente di passare i puntatori nei contenitori alla modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Restituisce il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [RequestCachePolicy](../requestcachepolicy/)
* Namespace [System::Net::Cache](../)
* Libreria [Aspose.Slides](../../)