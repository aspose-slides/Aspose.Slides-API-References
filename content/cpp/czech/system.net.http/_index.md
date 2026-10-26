---
title: "System::Net::Http"
second_title: Aspose.Slides pro C++ – Referenční příručka API
description: 
type: docs
weight: 677
url: /cs/system.net.http/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | Reprezentuje HTTP obsah jako pole bajtů. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k runtime chybám a/nebo chybám aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [Details_HttpRequestException](./details_httprequestexception/) | Základní výjimečná třída je vyhazována třídami [HttpClient](./httpclient/) a [HttpMessageHandler](./httpmessagehandler/). Nikdy nevytvářejte instance této třídy ručně. Použijte třídu HttpRequestException místo ní. Nikdy nezabaluje instance třídy HttpRequestException do [System::SmartPtr](../system/smartptr/). |
| [HttpClient](./httpclient/) | Reprezentuje základní třídu HTTP klienta pro odesílání požadavků a přijímání odpovědí. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k runtime chybám a/nebo chybám aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [HttpClientHandler](./httpclienthandler/) | Reprezentuje výchozí zpracovatele zpráv používaný třídou [HttpClient](./httpclient/). Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k runtime chybám a/nebo chybám aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [HttpContent](./httpcontent/) | Reprezentuje obsah HTTP entity. [Object](../system/object/) této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k runtime chybám a/nebo chybám aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [HttpMessageHandler](./httpmessagehandler/) | Reprezentuje základní typ pro HTTP zpracovatele zpráv. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k runtime chybám a/nebo chybám aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [HttpMessageInvoker](./httpmessageinvoker/) | Umožňuje aplikacím volat metodu Send v řetězci HTTP zpracovatelů. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k runtime chybám a/nebo chybám aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [HttpMethod](./httpmethod/) | Reprezentuje HTTP metodu. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k runtime chybám a/nebo chybám aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [HttpRequestMessage](./httprequestmessage/) | Reprezentuje HTTP požadavek. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k runtime chybám a/nebo chybám aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [HttpResponseMessage](./httpresponsemessage/) | Reprezentuje HTTP odpověď. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k runtime chybám a/nebo chybám aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [HttpUtilities](./httputilities/) | Obsahuje pomocné metody. |
| [StringContent](./stringcontent/) | Reprezentuje HTTP obsah jako řetězec. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k runtime chybám a/nebo chybám aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
## Funkce

| Funkce | Popis |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
## Výčty

| Výčet | Popis |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | Určuje, kdy by měla být operace [HttpClient](./httpclient/) dokončena. |
| [HttpParseResult](./httpparseresult/) | Určuje výsledek parsování. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |