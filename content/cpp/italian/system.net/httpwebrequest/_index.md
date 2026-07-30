---
title: HttpWebRequest
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta la richiesta web HTTP. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e utilizzare tale puntatore per passarla alle funzioni come argomento."
type: docs
weight: 274
url: /it/system.net/httpwebrequest/
---
## HttpWebRequest classe


Rappresenta la richiesta web HTTP. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa quel puntatore per passarlo alle funzioni come argomento.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [Abort](./abort/)() override | Interrompe la richiesta corrente. |
| virtual void [AddRange](./addrange/)(**int32_t**) | Aggiunge l'intestazione '[Range](../../system/range/)' alla richiesta corrente. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | Aggiunge l'intestazione '[Range](../../system/range/)' alla richiesta corrente. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Avvia un'operazione asincrona per ottenere uno stream per scrivere dati nella risorsa. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Avvia una richiesta asincrona per la risorsa. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | Crea una nuova istanza della classe [WebRequest](../webrequest/) usando l'URI specificato. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Crea una nuova istanza della classe [WebRequest](../webrequest/) usando l'URI specificato. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Crea un discendente [WebRequest](../webrequest/) per lo schema URI specificato. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | Crea una nuova istanza della classe [WebRequest](../webrequest/) usando l'URI specificato. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Crea una nuova istanza della classe [WebRequest](../webrequest/) usando l'URI specificato. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Attende fino al completamento dell'operazione asincrona specificata per ottenere lo stream. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Attende fino al completamento della richiesta asincrona specificata per la risorsa. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | Restituisce il valore dell'intestazione HTTP 'Accept'. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Restituisce un valore che indica se la richiesta deve seguire i redirect. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Restituisce un valore che indica se i dati ricevuti dalla risorsa devono essere memorizzati in buffer. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Restituisce un valore che indica se il buffering è abilitato per l'invio dei dati. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | Restituisce la politica di cache. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Restituisce la collezione dei certificati associati alla richiesta corrente. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | Restituisce il nome del gruppo di connessione. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | Restituisce il numero di byte dei dati della richiesta da inviare. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Restituisce il tipo MIME della richiesta. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | Restituisce un timeout per attendere il codice di stato 100-Continue. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Restituisce un contenitore di cookie associato alla richiesta web corrente. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | Restituisce le informazioni di autenticazione associate alla richiesta corrente. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | Restituisce il proxy HTTP globale. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | Restituisce un valore che indica se è stata ricevuta una risposta. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | Restituisce la collezione delle intestazioni HTTP. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | Restituisce un valore che indica se la richiesta corrente deve contenere l'intestazione 'Keep-Alive'. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Restituisce il numero massimo di redirect consentiti. |
| [String](../../system/string/) [get_Method](./get_method/)() override | Restituisce il metodo HTTP. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | Restituisce un valore che indica se la richiesta deve essere pre-autenticata. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | Restituisce l'elenco dei prefissi. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | Restituisce il proxy HTTP. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | Restituisce il valore dell'intestazione 'Referer'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | Restituisce l'URI della richiesta. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | Restituisce un valore che indica se i dati devono essere inviati in segmenti. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | Restituisce un punto di servizio che rappresenta la connessione di rete alla risorsa. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Restituisce un valore che indica se la richiesta corrente può usare un contenitore di cookie. |
| **int32_t** [get_Timeout](./get_timeout/)() override | Restituisce un intervallo di tempo in millisecondi dopo il quale la richiesta scadrà. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Restituisce un valore che indica se la proprietà 'Credential' è uguale alla proprietà 'DefaultCredentials'. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | Restituisce il valore dell'intestazione 'User-Agent'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Restituisce la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | Restituisce lo stream per scrivere dati nella risorsa. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | Restituisce la risposta web associata alla richiesta web corrente. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Restituisce il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Costruisce una nuova istanza. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita il clonado di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Registra il discendente [WebRequest](../webrequest/) per l'URI specificato. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | Imposta il valore dell'intestazione HTTP 'Accept'. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Imposta un valore che indica se la richiesta deve seguire i redirect. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | Imposta un valore che indica se i dati ricevuti dalla risorsa devono essere memorizzati in buffer. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | Imposta un valore che indica se il buffering è abilitato per l'invio dei dati. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Imposta la politica di cache. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | Imposta la collezione dei certificati associati alla richiesta corrente. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | Imposta il nome del gruppo di connessione. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | Imposta il numero di byte dei dati della richiesta da inviare. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | Imposta il tipo MIME della richiesta. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | Imposta un timeout per attendere il codice di stato 100-Continue. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | Imposta un contenitore di cookie associato alla richiesta web corrente. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | Imposta le informazioni di autenticazione associate alla richiesta corrente. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Imposta il proxy HTTP globale. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | Imposta la collezione delle intestazioni HTTP. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | Imposta un valore che indica se la richiesta corrente deve contenere l'intestazione 'Keep-Alive'. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Imposta il numero massimo di redirect consentiti. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | Imposta il metodo HTTP. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | Imposta un valore che indica se la richiesta deve essere pre-autenticata. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Imposta l'elenco dei prefissi. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | Imposta la versione di HTTP. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | Imposta il proxy HTTP. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | Imposta il valore dell'intestazione 'Referer'. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | Imposta un valore che indica se i dati devono essere inviati in segmenti. |
| void [set_Timeout](./set_timeout/)(int) override | Imposta un intervallo di tempo in millisecondi dopo il quale la richiesta scadrà. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | Imposta un intervallo di tempo in millisecondi dopo il quale la richiesta scadrà. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | Imposta un valore che indica se la proprietà 'Credential' è uguale alla proprietà 'DefaultCredentials'. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | Imposta il valore dell'intestazione 'User-Agent'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un weak pointer (piuttosto che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Restituisce il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruttura C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Vedi anche

* Classe [WebRequest](../webrequest/)
* Spazio dei nomi [System::Net](../)
* Libreria [Aspose.Slides](../../)