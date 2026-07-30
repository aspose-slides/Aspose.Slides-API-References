---
title: "System::Web::Services::Protocols"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 1080
url: /it/system.web.services.protocols/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | Rappresenta l'eccezione generata quando il metodo è chiamato tramite SOAP e si verifica un errore. Non creare mai istanze di questa classe manualmente. Usa invece la classe SoapException. Non inserire mai le istanze della classe SoapException in [System::SmartPtr](../system/smartptr/). |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | Questa classe base è usata in tutti i proxy client di servizio XML [Web](../system.web/) che utilizzano HTTP. Gli oggetti di questa classe devono essere allocati solo tramite la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarlo alle funzioni come argomento. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | Un'istanza di questa classe viene passata come argomento al delegato InvokeCompletedEventHandler. Gli oggetti di questa classe devono essere allocati solo tramite la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarlo alle funzioni come argomento. |
| [SoapClientMessage](./soapclientmessage/) | Rappresenta i dati in una richiesta SOAP inviata o in una risposta SOAP ricevuta. Gli oggetti di questa classe devono essere allocati solo tramite la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarlo alle funzioni come argomento. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | Specifica che tutti i messaggi SOAP passati o restituiti dal metodo utilizzano la formattazione Document. Gli oggetti di questa classe devono essere allocati solo tramite la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarlo alle funzioni come argomento. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | Imposta il formato predefinito per le richieste e le risposte SOAP. Gli oggetti di questa classe devono essere allocati solo tramite la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarlo alle funzioni come argomento. |
| [SoapHeader](./soapheader/) | Rappresenta il contenuto dell'intestazione SOAP. Gli oggetti di questa classe devono essere allocati solo tramite la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarlo alle funzioni come argomento. |
| [SoapHeaderAttribute](./soapheaderattribute/) | Specifica l'intestazione SOAP che il metodo di servizio XML [Web](../system.web/) o il client di servizio XML [Web](../system.web/) può elaborare. Gli oggetti di questa classe devono essere allocati solo tramite la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarlo alle funzioni come argomento. |
| [SoapHeaderCollection](./soapheadercollection/) | Contiene una collezione di istanze della classe [SoapHeader](./soapheader/). |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | I servizi proxy client devono ereditare questa classe quando si utilizza SOAP. Gli oggetti di questa classe devono essere allocati solo tramite la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarlo alle funzioni come argomento. |
| [SoapMessage](./soapmessage/) | Rappresenta il messaggio SOAP. Gli oggetti di questa classe devono essere allocati solo tramite la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarlo alle funzioni come argomento. |
| [WebClientProtocol](./webclientprotocol/) | Questa classe base è usata in tutti i proxy client di servizio XML [Web](../system.web/) che sono stati creati usando ASP.NET. Gli oggetti di questa classe devono essere allocati solo tramite la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarlo alle funzioni come argomento. |

## Enumerazioni

| Enumerazione | Descrizione |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | Enumera le direzioni dell'intestazione SOAP. |
| [SoapMessageStage](./soapmessagestage/) | Enumera le fasi di elaborazione dei messaggi SOAP. |
| [SoapParameterStyle](./soapparameterstyle/) | Enumera i formati dei parametri in un messaggio SOAP. |
| [SoapProtocolVersion](./soapprotocolversion/) | Enumera le versioni di SOAP. |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | Enumera le opzioni su come un messaggio SOAP viene instradato al servizio XML [Web](../system.web/). |

## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [SoapException](./soapexception/) |  |