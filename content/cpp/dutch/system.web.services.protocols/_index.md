---
title: "System::Web::Services::Protocols"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 1080
url: /nl/system.web.services.protocols/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | Vertegenwoordigt de uitzondering die wordt gegooid wanneer een methode wordt aangeroepen via SOAP en er een fout optreedt. Maak nooit handmatig exemplaren van deze klasse. Gebruik in plaats daarvan de SoapException-klasse. Verpak nooit de SoapException-klasse-instanties in [System::SmartPtr](../system/smartptr/). |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | Deze basisklasse wordt gebruikt in alle XML [Web](../system.web/) service-client-proxy’s die HTTP gebruiken. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | Een exemplaar van deze klasse wordt als argument doorgegeven aan de InvokeCompletedEventHandler-delegate. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [SoapClientMessage](./soapclientmessage/) | Vertegenwoordigt de gegevens in een SOAP-verzoek dat is verzonden of een SOAP-antwoord dat is ontvangen. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | Geeft aan dat alle SOAP-berichten die aan de methode worden doorgegeven of ervan worden teruggegeven de Document-opmaak gebruiken. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | Stelt het standaardformaat in voor de SOAP-verzoeken en -antwoorden. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [SoapHeader](./soapheader/) | Vertegenwoordigt de inhoud van de SOAP-header. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [SoapHeaderAttribute](./soapheaderattribute/) | Geeft de SOAP-header op die de XML [Web](../system.web/) service-methode of de XML [Web](../system.web/) service-client kan verwerken. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [SoapHeaderCollection](./soapheadercollection/) | Bevat een collectie van exemplaren van de [SoapHeader](./soapheader/)-klasse. |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | De client-proxy-services moeten deze klasse erven wanneer SOAP wordt gebruikt. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [SoapMessage](./soapmessage/) | Vertegenwoordigt het SOAP-bericht. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [WebClientProtocol](./webclientprotocol/) | Deze basisklasse wordt gebruikt in alle XML [Web](../system.web/) service-client-proxy’s die zijn aangemaakt met ASP.NET. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | Somt de richtingen van de SOAP-header op. |
| [SoapMessageStage](./soapmessagestage/) | Somt de verwerkingsstadia van de SOAP-berichten op. |
| [SoapParameterStyle](./soapparameterstyle/) | Somt de parameterformaten in een SOAP-bericht op. |
| [SoapProtocolVersion](./soapprotocolversion/) | Somt de versies van SOAP op. |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | Somt de opties op hoe een SOAP-bericht wordt gerouteerd naar de XML [Web](../system.web/)-service. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [SoapException](./soapexception/) |  |