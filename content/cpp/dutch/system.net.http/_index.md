---
title: "System::Net::Http"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 677
url: /nl/system.net.http/
---
## Klassen

| Class | Description |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | Representeert HTTP-inhoud als een byte-array. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies door te geven als argument. |
| [Details_HttpRequestException](./details_httprequestexception/) | De basis-exception-klasse wordt gegooid door de [HttpClient](./httpclient/) en [HttpMessageHandler](./httpmessagehandler/) klassen. Maak nooit handmatig instanties van deze klasse. Gebruik in plaats daarvan de HttpRequestException-klasse. Wikkel de HttpRequestException-klasse-instanties nooit in [System::SmartPtr](../system/smartptr/). |
| [HttpClient](./httpclient/) | Representeert een basis-klasse van een HTTP-client voor het verzenden van verzoeken en het ontvangen van antwoorden. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies door te geven als argument. |
| [HttpClientHandler](./httpclienthandler/) | Representeert de standaard-bericht-handler die wordt gebruikt door de [HttpClient](./httpclient/) klasse. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies door te geven als argument. |
| [HttpContent](./httpcontent/) | Representeert de inhoud van een HTTP-entity. [Object](../system/object/) van deze klasse mag alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies door te geven als argument. |
| [HttpMessageHandler](./httpmessagehandler/) | Representeert een basistype voor de HTTP-bericht-handlers. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies door te geven als argument. |
| [HttpMessageInvoker](./httpmessageinvoker/) | Staat applicaties toe om de Send-methode aan te roepen op een HTTP-handler-keten. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies door te geven als argument. |
| [HttpMethod](./httpmethod/) | Representeert een HTTP-methode. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies door te geven als argument. |
| [HttpRequestMessage](./httprequestmessage/) | Representeert een HTTP-verzoek-bericht. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies door te geven als argument. |
| [HttpResponseMessage](./httpresponsemessage/) | Representeert een HTTP-respons-bericht. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies door te geven als argument. |
| [HttpUtilities](./httputilities/) | Bevat de hulpmethoden. |
| [StringContent](./stringcontent/) | Representeert HTTP-inhoud als een string. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies door te geven als argument. |
## Functies

| Function | Description |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
## Enumeraties

| Enum | Description |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | Geeft aan wanneer een [HttpClient](./httpclient/)-operatie moet worden voltooid. |
| [HttpParseResult](./httpparseresult/) | Geeft het parse-resultaat aan. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |