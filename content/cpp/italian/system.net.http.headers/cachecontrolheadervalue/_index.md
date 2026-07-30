---
title: CacheControlHeaderValue
second_title: Aspose.Slides per C++ API Reference
description: "Rappresenta un valore dell'intestazione 'Cache-Control'. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o violazioni di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e utilizzare tale puntatore per passarla alle funzioni come argomento."
type: docs
weight: 14
url: /it/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue classe

Rappresenta un valore dell'intestazione 'Cache-Control'. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché causerà errori di runtime e/o violazioni di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usare tale puntatore per passarla alle funzioni come argomento.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Crea una nuova istanza. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Restituisce la collezione dei token di estensione della cache. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Ottiene il valore di età massima in secondi che determina il periodo durante il quale il client accetterà una risposta. |
| **bool** [get_MaxStale](./get_maxstale/)() | Ottiene il valore che determina se il client accetterà le risposte scadute. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Ottiene il valore in secondi che determina il periodo durante il quale il client accetterà le risposte scadute. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Ottiene il valore che determina la durata della freschezza. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Ottiene il valore che determina se il server richiede la rivalidazione di una voce della cache quando questa diventa obsoleta. |
| **bool** [get_NoCache](./get_nocache/)() | Ottiene il valore che determina se il client accetterà una risposta cacheata. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Ottiene la collezione dei nomi dei campi nella direttiva 'no-cache' dell'intestazione 'Cache-Control'. |
| **bool** [get_NoStore](./get_nostore/)() | Ottiene il valore che determina se una cache non deve memorizzare alcuna parte di una richiesta o risposta HTTP. |
| **bool** [get_NoTransform](./get_notransform/)() | Ottiene il valore che determina se una cache o un proxy non devono modificare alcuna parte del corpo dell'entità. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Ottiene il valore che determina se il client deve usare solo voci cacheate. |
| **bool** [get_Private](./get_private/)() | Ottiene il valore che determina se il messaggio di risposta HTTP o la sua parte è destinato a un singolo utente e non deve essere memorizzato da una cache condivisa. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Ottiene la collezione dei nomi dei campi nella direttiva 'private' dell'intestazione 'Cache-Control'. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Ottiene il valore che determina se il server richiede la rivalidazione di una voce di cache quando diventa obsoleta per le cache condivise degli agenti utente. |
| **bool** [get_Public](./get_public/)() | Ottiene il valore che determina se una risposta HTTP può essere memorizzata da qualsiasi cache. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Ottiene il valore di età massima condivisa in secondi che sovrascrive la direttiva 'max-age' nell'intestazione 'Cache-Control' o l'intestazione 'Expires' per una cache condivisa. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Converte una stringa fornita dall'indice specificato in un'istanza della classe [CacheControlHeaderValue](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Converte una stringa fornita in un'istanza della classe [CacheControlHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Imposta il valore di età massima in secondi che determina il periodo durante il quale il client accetterà una risposta. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Imposta il valore che determina se il client accetterà le risposte scadute. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Imposta il valore in secondi che determina il periodo durante il quale il client accetterà le risposte scadute. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Imposta il valore che determina la durata della freschezza. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Imposta il valore che determina se il server richiede la rivalidazione di una voce di cache quando questa diventa obsoleta. |
| void [set_NoCache](./set_nocache/)(**bool**) | Imposta il valore che determina se il client accetterà una risposta cacheata. |
| void [set_NoStore](./set_nostore/)(**bool**) | Imposta il valore che determina se una cache non deve memorizzare alcuna parte di una richiesta o risposta HTTP. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Imposta il valore che determina se una cache o un proxy non devono modificare alcuna parte del corpo dell'entità. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Imposta il valore che determina se il client deve usare solo voci cacheate. |
| void [set_Private](./set_private/)(**bool**) | Imposta il valore che determina se il messaggio di risposta HTTP o la sua parte è destinato a un singolo utente e non deve essere memorizzato da una cache condivisa. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Imposta il valore che determina se il server richiede la rivalidazione di una voce di cache quando diventa obsoleta per le cache condivise degli agenti utente. |
| void [set_Public](./set_public/)(**bool**) | Imposta il valore che determina se una risposta HTTP può essere memorizzata da qualsiasi cache. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Imposta il valore di età massima condivisa in secondi che sovrascrive la direttiva 'max-age' nell'intestazione 'Cache-Control' o l'intestazione 'Expires' per una cache condivisa. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Tenta di convertire una stringa fornita in un'istanza della classe [CacheControlHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [ICloneable](../../system/icloneable/)
* Spazio dei nomi [System::Net::Http::Headers](../)
* Libreria [Aspose.Slides](../../)