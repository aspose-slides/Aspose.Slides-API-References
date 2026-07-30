---
title: HttpResponseMessage
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta un messaggio di risposta HTTP. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject() . Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 118
url: /it/system.net.http/httpresponsemessage/
---
## HttpResponseMessage classe

Rappresenta un messaggio di risposta HTTP. Gli oggetti di questa classe dovrebbero essere istanziati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o violazioni di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e utilizza tale puntatore per passarla alle funzioni come argomento.

```cpp
class HttpResponseMessage : public System::IDisposable
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [Dispose](./dispose/)() override | Rilascia l'istanza corrente. Questo metodo rilascia anche il contenuto della risposta HTTP. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpResponseMessage](./)\> [EnsureSuccessStatusCode](./ensuresuccessstatuscode/)() | Verifica il codice di stato. HttpRequestException verrà lanciata quando il codice di stato non appartiene alla gamma 2xx. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali, anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali, anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\> [get_Content](./get_content/)() const | Ottiene il contenuto della risposta HTTP. |
| [System::SharedPtr](../../system/sharedptr/)\<[Headers::HttpResponseHeaders](../../system.net.http.headers/httpresponseheaders/)\> [get_Headers](./get_headers/)() const | Restituisce le intestazioni del contenuto HTTP. |
| **bool** [get_IsSuccessStatusCode](./get_issuccessstatuscode/)() const | Verifica se il codice di stato indica che l'azione richiesta dal client è stata ricevuta, compresa e accettata. |
| [String](../../system/string/) [get_ReasonPhrase](./get_reasonphrase/)() const | Ottiene la Reason-Phrase inviata dai server insieme al codice di stato. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\> [get_RequestMessage](./get_requestmessage/)() const | Ottiene il messaggio di richiesta HTTP. |
| [HttpStatusCode](../../system.net/httpstatuscode/) [get_StatusCode](./get_statuscode/)() const | Ottiene il codice di stato HTTP. |
| [System::Version](../../system/version/) [get_Version](./get_version/)() const | Ottiene la versione HTTP. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Restituisce il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpResponseMessage](./httpresponsemessage/)() | Costruisce una nuova istanza. |
|  [HttpResponseMessage](./httpresponsemessage/)([HttpStatusCode](../../system.net/httpstatuscode/)) | Costruisce una nuova istanza. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, davvero, ma inizializza un nuovo oggetto e consente la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, davvero, ma inizializza un nuovo oggetto e consente la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso di un valore specificato. |
| void [set_Content](./set_content/)([System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\>) | Imposta il contenuto della risposta HTTP. |
| void [set_ReasonPhrase](./set_reasonphrase/)([String](../../system/string/)) | Imposta la Reason-Phrase inviata dai server insieme al codice di stato. |
| void [set_RequestMessage](./set_requestmessage/)([System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\>) | Imposta il messaggio di richiesta HTTP. |
| void [set_StatusCode](./set_statuscode/)([HttpStatusCode](../../system.net/httpstatuscode/)) | Imposta il codice di stato HTTP. |
| void [set_Version](./set_version/)([System::Version](../../system/version/)) | Imposta la versione HTTP. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore weak (piuttosto che shared). Consente di passare i puntatori nei contenitori alla modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | [System::Object::ToString](../../system/object/tostring/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Libreria [Aspose.Slides](../../)