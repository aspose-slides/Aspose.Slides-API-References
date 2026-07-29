---
title: "System::Web::Services::Protocols"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 1080
url: /sv/system.web.services.protocols/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | Representerar undantaget som kastas när metoden anropas över SOAP och ett fel inträffar. Skapa aldrig instanser av den här klassen manuellt. Använd SoapException-klassen istället. Paketera aldrig SoapException-klassens instanser i [System::SmartPtr](../system/smartptr/). |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | Denna basklass används i alla XML [Web](../system.web/) tjänsteklientproxier som använder HTTP. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller assert-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använda pekaren för att skicka den till funktioner som argument. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | En instans av denna klass överförs som argument till InvokeCompletedEventHandler-delegaten. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller assert-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använda pekaren för att skicka den till funktioner som argument. |
| [SoapClientMessage](./soapclientmessage/) | Representerar data i en SOAP-förfrågan som skickas eller ett SOAP-svar som mottagits. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller assert-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använda pekaren för att skicka den till funktioner som argument. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | Anger att alla SOAP-meddelanden som skickas eller returneras från metoden använder Document-formatet. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller assert-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använda pekaren för att skicka den till funktioner som argument. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | Ställer in standardformatet för SOAP-förfrågningar och svar. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller assert-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använda pekaren för att skicka den till funktioner som argument. |
| [SoapHeader](./soapheader/) | Representerar innehållet i SOAP-headern. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller assert-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använda pekaren för att skicka den till funktioner som argument. |
| [SoapHeaderAttribute](./soapheaderattribute/) | Anger den SOAP-header som XML [Web](../system.web/)-tjänstemetoden eller XML [Web](../system.web/)-tjänsteklienten kan bearbeta. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller assert-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använda pekaren för att skicka den till funktioner som argument. |
| [SoapHeaderCollection](./soapheadercollection/) | Innehåller en samling av instanser av klassen [SoapHeader](./soapheader/). |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | Klientproxytjänster måste ärva denna klass när SOAP används. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller assert-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använda pekaren för att skicka den till funktioner som argument. |
| [SoapMessage](./soapmessage/) | Representerar SOAP-meddelandet. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller assert-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använda pekaren för att skicka den till funktioner som argument. |
| [WebClientProtocol](./webclientprotocol/) | Denna basklass används i alla XML [Web](../system.web/)-tjänsteklientproxier som skapades med ASP.NET. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller assert-fel. Paketera alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använda pekaren för att skicka den till funktioner som argument. |

## Uppräkningar

| Enum | Beskrivning |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | Enumererar riktningarna för SOAP-headern. |
| [SoapMessageStage](./soapmessagestage/) | Enumererar bearbetningsstegen för SOAP-meddelanden. |
| [SoapParameterStyle](./soapparameterstyle/) | Enumererar parameterformaten i ett SOAP-meddelande. |
| [SoapProtocolVersion](./soapprotocolversion/) | Enumererar versionerna av SOAP. |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | Enumererar alternativ för hur ett SOAP-meddelande dirigeras till XML [Web](../system.web/)-tjänsten. |

## Typdef

| Typedef | Beskrivning |
| --- | --- |
| [SoapException](./soapexception/) |  |