---
title: "System::Net::Http"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 677
url: /de/system.net.http/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | Stellt HTTP-Inhalt als Byte-Array dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [Details_HttpRequestException](./details_httprequestexception/) | Die Basisausnahmeklasse wird von den Klassen [HttpClient](./httpclient/) und [HttpMessageHandler](./httpmessagehandler/) geworfen. Erstellen Sie niemals Instanzen dieser Klasse manuell. Verwenden Sie stattdessen die Klasse HttpRequestException. Wickeln Sie die Instanzen der Klasse HttpRequestException niemals in [System::SmartPtr](../system/smartptr/) ein. |
| [HttpClient](./httpclient/) | Stellt eine Basisklasse eines HTTP-Clients zum Senden von Anfragen und Empfangen von Antworten dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [HttpClientHandler](./httpclienthandler/) | Stellt den Standardnachrichten-Handler dar, der von der Klasse [HttpClient](./httpclient/) verwendet wird. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [HttpContent](./httpcontent/) | Stellt den Inhalt einer HTTP-Entität dar. [Object](../system/object/) dieser Klasse sollte nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [HttpMessageHandler](./httpmessagehandler/) | Stellt einen Basistyp für die HTTP-Nachrichten-Handler dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [HttpMessageInvoker](./httpmessageinvoker/) | Ermöglicht Anwendungen, die Send-Methode in einer HTTP-Handler-Kette aufzurufen. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [HttpMethod](./httpmethod/) | Stellt eine HTTP-Methode dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [HttpRequestMessage](./httprequestmessage/) | Stellt eine HTTP-Anforderungsnachricht dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [HttpResponseMessage](./httpresponsemessage/) | Stellt eine HTTP-Antwortnachricht dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [HttpUtilities](./httputilities/) | Enthält die Hilfsmethoden. |
| [StringContent](./stringcontent/) | Stellt HTTP-Inhalt als Zeichenkette dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |

## Funktionen

| Funktion | Beschreibung |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |

## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | Gibt an, wann ein [HttpClient](./httpclient/)-Vorgang abgeschlossen sein soll. |
| [HttpParseResult](./httpparseresult/) | Gibt das Parsergebnis an. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |