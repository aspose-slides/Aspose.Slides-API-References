---
title: "System::Web::Services::Protocols"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 1080
url: /de/system.web.services.protocols/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | Stellt die Ausnahme dar, die ausgelöst wird, wenn die Methode über SOAP aufgerufen wird und ein Fehler auftritt. Erzeugen Sie niemals manuell Instanzen dieser Klasse. Verwenden Sie stattdessen die SoapException Klasse. Wickeln Sie SoapException Klasseninstanzen niemals in [System::SmartPtr](../system/smartptr/) ein. |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | Diese Basisklasse wird in allen XML [Web](../system.web/) Service-Client-Proxy-Klassen verwendet, die HTTP nutzen. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in den Zeiger [System::SmartPtr](../system/smartptr/) ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | Eine Instanz dieser Klasse wird als Argument an den InvokeCompletedEventHandler-Delegaten übergeben. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in den Zeiger [System::SmartPtr](../system/smartptr/) ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [SoapClientMessage](./soapclientmessage/) | Stellt die Daten in einer gesendeten SOAP-Anfrage oder einer empfangenen SOAP-Antwort dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in den Zeiger [System::SmartPtr](../system/smartptr/) ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | Gibt an, dass alle SOAP-Nachrichten, die an die Methode übergeben oder von ihr zurückgegeben werden, das Dokumentformat verwenden. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in den Zeiger [System::SmartPtr](../system/smartptr/) ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | Legt das Standardformat für SOAP-Anfragen und -Antworten fest. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in den Zeiger [System::SmartPtr](../system/smartptr/) ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [SoapHeader](./soapheader/) | Stellt den Inhalt des SOAP-Headers dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in den Zeiger [System::SmartPtr](../system/smartptr/) ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [SoapHeaderAttribute](./soapheaderattribute/) | Gibt den SOAP-Header an, den die XML [Web](../system.web/) Service-Methode oder der XML [Web](../system.web/) Service-Client verarbeiten kann. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in den Zeiger [System::SmartPtr](../system/smartptr/) ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [SoapHeaderCollection](./soapheadercollection/) | Enthält eine Sammlung von Instanzen der Klasse [SoapHeader](./soapheader/). |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | Die Client-Proxy-Dienste müssen diese Klasse erben, wenn SOAP verwendet wird. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in den Zeiger [System::SmartPtr](../system/smartptr/) ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [SoapMessage](./soapmessage/) | Stellt die SOAP-Nachricht dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in den Zeiger [System::SmartPtr](../system/smartptr/) ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [WebClientProtocol](./webclientprotocol/) | Diese Basisklasse wird in allen XML [Web](../system.web/) Service-Client-Proxys verwendet, die mit ASP.NET erstellt wurden. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in den Zeiger [System::SmartPtr](../system/smartptr/) ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |

## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | Listet die SOAP-Header-Richtungen auf. |
| [SoapMessageStage](./soapmessagestage/) | Listet die Verarbeitungsstufen der SOAP-Nachrichten auf. |
| [SoapParameterStyle](./soapparameterstyle/) | Listet die Parameterformate in einer SOAP-Nachricht auf. |
| [SoapProtocolVersion](./soapprotocolversion/) | Listet die SOAP-Versionen auf. |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | Listet Optionen, wie eine SOAP-Nachricht zum XML [Web](../system.web/) Service geroutet wird, auf. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [SoapException](./soapexception/) |  |