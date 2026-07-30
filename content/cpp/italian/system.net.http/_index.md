---
title: "System::Net::Http"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 677
url: /it/system.net.http/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | Rappresenta il contenuto HTTP come array di byte. Gli oggetti di questa classe devono essere allocati solo mediante la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o utilizzando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza questo puntatore per passarla alle funzioni come argomento. |
| [Details_HttpRequestException](./details_httprequestexception/) | La classe base di eccezione è sollevata dalle classi [HttpClient](./httpclient/) e [HttpMessageHandler](./httpmessagehandler/). Non creare mai istanze di questa classe manualmente. Usa invece la classe HttpRequestException. Non avvolgere le istanze della classe HttpRequestException in [System::SmartPtr](../system/smartptr/). |
| [HttpClient](./httpclient/) | Rappresenta una classe base di un client HTTP per l'invio di richieste e la ricezione di risposte. Gli oggetti di questa classe devono essere allocati solo mediante la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o utilizzando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza questo puntatore per passarla alle funzioni come argomento. |
| [HttpClientHandler](./httpclienthandler/) | Rappresenta il gestore di messaggi predefinito utilizzato dalla classe [HttpClient](./httpclient/). Gli oggetti di questa classe devono essere allocati solo mediante la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o utilizzando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza questo puntatore per passarla alle funzioni come argomento. |
| [HttpContent](./httpcontent/) | Rappresenta il contenuto di un'entità HTTP. [Object](../system/object/) di questa classe deve essere allocata solo mediante la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o utilizzando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza questo puntatore per passarla alle funzioni come argomento. |
| [HttpMessageHandler](./httpmessagehandler/) | Rappresenta un tipo base per i gestori di messaggi HTTP. Gli oggetti di questa classe devono essere allocati solo mediante la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o utilizzando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza questo puntatore per passarla alle funzioni come argomento. |
| [HttpMessageInvoker](./httpmessageinvoker/) | Consente alle applicazioni di chiamare il metodo Send su una catena di gestori HTTP. Gli oggetti di questa classe devono essere allocati solo mediante la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o utilizzando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza questo puntatore per passarla alle funzioni come argomento. |
| [HttpMethod](./httpmethod/) | Rappresenta un metodo HTTP. Gli oggetti di questa classe devono essere allocati solo mediante la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o utilizzando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza questo puntatore per passarla alle funzioni come argomento. |
| [HttpRequestMessage](./httprequestmessage/) | Rappresenta un messaggio di richiesta HTTP. Gli oggetti di questa classe devono essere allocati solo mediante la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o utilizzando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza questo puntatore per passarla alle funzioni come argomento. |
| [HttpResponseMessage](./httpresponsemessage/) | Rappresenta un messaggio di risposta HTTP. Gli oggetti di questa classe devono essere allocati solo mediante la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o utilizzando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza questo puntatore per passarla alle funzioni come argomento. |
| [HttpUtilities](./httputilities/) | Contiene i metodi di utilità. |
| [StringContent](./stringcontent/) | Rappresenta il contenuto HTTP come stringa. Gli oggetti di questa classe devono essere allocati solo mediante la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o utilizzando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza questo puntatore per pasarla alle funzioni come argomento. |

## Funzioni

| Funzione | Descrizione |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |

## Enumerazioni

| Enumerazione | Descrizione |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | Indica quando un'operazione [HttpClient](./httpclient/) deve essere completata. |
| [HttpParseResult](./httpparseresult/) | Indica il risultato dell'analisi. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |