---
title: SoapClientMessage
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta i dati in una richiesta SOAP inviata o in una risposta SOAP ricevuta. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiche' ciò provochera' errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e utilizzare questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 40
url: /it/system.web.services.protocols/soapclientmessage/
---
## SoapClientMessage class

Rappresenta i dati in una richiesta SOAP inviata o in una risposta SOAP ricevuta. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class SoapClientMessage : public System::Web::Services::Protocols::SoapMessage
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [CollectHeaders](../soapmessage/collectheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, [SoapHeaderDirection](../soapheaderdirection/)) | Imposta la collezione interna delle intestazioni SOAP. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\> [FindHeader](../soapmessage/findheader/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, const [TypeInfo](../../system/typeinfo/)\&) | Trova la mappatura dell'intestazione per il tipo di intestazione specificato. |
| [String](../../system/string/) [get_Action](./get_action/)() override | Restituisce il valore dell'attributo 'SOAPAction'. |
| [System::SharedPtr](../../system/sharedptr/)\<[SoapHttpClientProtocol](../soaphttpclientprotocol/)\> [get_Client](./get_client/)() | Restituisce un'istanza della classe proxy del client. |
| [String](../../system/string/) [get_ContentEncoding](../soapmessage/get_contentencoding/)() | Recupera un valore dell'intestazione 'Content-Encoding'. |
| [String](../../system/string/) [get_ContentType](../soapmessage/get_contenttype/)() | Recupera un valore dell'intestazione 'Content-Type'. |
| [SoapException](../soapexception/) [get_Exception](../soapmessage/get_exception/)() | Recupera l'eccezione lanciata dal metodo di servizio XML [Web](../../system.web/). |
| [System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\> [get_Headers](../soapmessage/get_headers/)() | Recupera la collezione delle intestazioni SOAP. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_InParameters](../soapmessage/get_inparameters/)() | Recupera i parametri passati al metodo di servizio XML [Web](../../system.web/). |
| **bool** [get_IsSoap12](../soapmessage/get_issoap12/)() | Restituisce un valore che indica se è in uso la versione SOAP 1.2. |
| virtual **bool** [get_OneWay](./get_oneway/)() | Restituisce un valore che indica se un client non attende il completamento del metodo da parte del server. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_OutParameters](../soapmessage/get_outparameters/)() | Recupera i parametri di output passati al metodo di servizio XML [Web](../../system.web/). |
| [SoapProtocolVersion](../soapprotocolversion/) [get_SoapVersion](./get_soapversion/)() override | Restituisce la versione SOAP in uso. |
| [SoapMessageStage](../soapmessagestage/) [get_Stage](../soapmessage/get_stage/)() | Recupera lo stadio di elaborazione di un messaggio SOAP. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [get_Stream](../soapmessage/get_stream/)() | Recupera lo stream che contiene i dati del messaggio SOAP. |
| [String](../../system/string/) [get_Url](./get_url/)() override | Restituisce l'URL del servizio XML [Web](../../system.web/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Recupera la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetInParameterValue](../soapmessage/getinparametervalue/)(**int32_t**) | Recupera il valore del parametro di input all'indice specificato. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetOutParameterValue](../soapmessage/getoutparametervalue/)(**int32_t**) | Recupera il valore del parametro di output all'indice specificato. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetReturnValue](../soapmessage/getreturnvalue/)() | Recupera il valore di ritorno del metodo di servizio XML [Web](../../system.web/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Recupera il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la costruzione per copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la costruzione per copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| void [set_ContentEncoding](../soapmessage/set_contentencoding/)([String](../../system/string/)) | Imposta un valore dell'intestazione 'Content-Encoding'. |
| void [set_ContentType](../soapmessage/set_contenttype/)([String](../../system/string/)) | Imposta un valore dell'intestazione 'Content-Type'. |
| void [set_InParameters](../soapmessage/set_inparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | Imposta i parametri passati al metodo di servizio XML [Web](../../system.web/). |
| void [set_InternalStream](../soapmessage/set_internalstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Imposta lo stream che contiene i dati del messaggio SOAP. |
| void [set_OutParameters](../soapmessage/set_outparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | Imposta i parametri di output passati al metodo di servizio XML [Web](../../system.web/). |
| void [SetException](../soapmessage/setexception/)([SoapException](../soapexception/)) | Imposta l'eccezione lanciata dal metodo di servizio XML [Web](../../system.web/). |
| void [SetHeaders](../soapmessage/setheaders/)([System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\>) | Imposta la collezione delle intestazioni SOAP. |
| void [SetStage](../soapmessage/setstage/)([SoapMessageStage](../soapmessagestage/)) | Imposta lo stadio di elaborazione del messaggio SOAP. |
| void [SetStream](../soapmessage/setstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Imposta lo stream che contiene i dati del messaggio SOAP. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Recupera il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
|  [SoapClientMessage](./soapclientmessage/)([System::SharedPtr](../../system/sharedptr/)\<[SoapHttpClientProtocol](../soaphttpclientprotocol/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapMethodStubInfo\>, [String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | Costruisce una nuova istanza. |
|  [SoapMessage](../soapmessage/soapmessage/)() | Costruisce una nuova istanza. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| void [UpdateHeaderValues](../soapmessage/updateheadervalues/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>) | Aggiorna la collezione interna delle intestazioni SOAP. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [SoapMessage](../soapmessage/)
* Spazio dei nomi [System::Web::Services::Protocols](../)
* Libreria [Aspose.Slides](../../)