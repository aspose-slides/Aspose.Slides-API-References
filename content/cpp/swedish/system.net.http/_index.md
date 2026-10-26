---
title: "System::Net::Http"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 677
url: /sv/system.net.http/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | Representerar HTTP-innehåll som en byte-array. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Inslå alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [Details_HttpRequestException](./details_httprequestexception/) | Den grundläggande undantagsklassen kastas av klasserna [HttpClient](./httpclient/) och [HttpMessageHandler](./httpmessagehandler/). Skapa aldrig instanser av denna klass manuellt. Använd klassen HttpRequestException istället. Inslå aldrig HttpRequestException-klassen i [System::SmartPtr](../system/smartptr/). |
| [HttpClient](./httpclient/) | Representerar en basklass för en HTTP-klient för att skicka förfrågningar och ta emot svar. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Inslå alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [HttpClientHandler](./httpclienthandler/) | Representerar standardmeddelandehanteraren som används av klassen [HttpClient](./httpclient/). Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Inslå alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [HttpContent](./httpcontent/) | Representerar innehållet i en HTTP-entity. [Object](../system/object/) av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Inslå alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [HttpMessageHandler](./httpmessagehandler/) | Representerar en bas-typ för HTTP-meddelandehanterare. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Inslå alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [HttpMessageInvoker](./httpmessageinvoker/) | Tillåter applikationer att anropa Send-metoden på en HTTP-hanteringskedja. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Inslå alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [HttpMethod](./httpmethod/) | Representerar en HTTP-metod. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Inslå alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [HttpRequestMessage](./httprequestmessage/) | Representerar ett HTTP-begärandemeddelande. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Inslå alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [HttpResponseMessage](./httpresponsemessage/) | Representerar ett HTTP-svarsmeddelande. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Inslå alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [HttpUtilities](./httputilities/) | Innehåller verktygsmetoderna. |
| [StringContent](./stringcontent/) | Representerar HTTP-innehåll som en sträng. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Inslå alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |

## Funktioner

| Funktion | Beskrivning |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |

## Enums

| Enum | Beskrivning |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | Anger när en [HttpClient](./httpclient/)-operation ska slutföras. |
| [HttpParseResult](./httpparseresult/) | Anger parsningens resultat. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |