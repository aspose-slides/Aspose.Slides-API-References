---
title: "System::Web::Services::Protocols"
second_title: Aspose.Slides pro C++ – referenční příručka API
description: 
type: docs
weight: 1080
url: /cs/system.web.services.protocols/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | Reprezentuje výjimku vyhozenou, když je metoda volána přes SOAP a nastane chyba. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu SoapException. Nikdy neobalujte instance třídy SoapException do [System::SmartPtr](../system/smartptr/). |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | Tato základní třída se používá ve všech XML [Web](../system.web/) service client proxy, které používají HTTP. Objektům této třídy by mělo být přidělováno pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | Instance této třídy se předává jako argument delegátu InvokeCompletedEventHandler. Objektům této třídy by mělo být přidělováno pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [SoapClientMessage](./soapclientmessage/) | Reprezentuje data v požadavku SOAP odeslaném nebo ve odpovědi SOAP přijaté. Objektům této třídy by mělo být přidělováno pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | Specifikuje, že všechny zprávy SOAP předávané nebo vrácené metodou používají formát Document. Objektům této třídy by mělo být přidělováno pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | Nastavuje výchozí formát pro požadavky a odpovědi SOAP. Objektům této třídy by mělo být přidělováno pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [SoapHeader](./soapheader/) | Reprezentuje obsah hlavičky SOAP. Objektům této třídy by mělo být přidělováno pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [SoapHeaderAttribute](./soapheaderattribute/) | Specifikuje hlavičku SOAP, kterou může zpracovat metoda služby XML [Web](../system.web/) nebo klient služby XML [Web](../system.web/). Objektům této třídy by mělo být přidělováno pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [SoapHeaderCollection](./soapheadercollection/) | Obsahuje kolekci instancí třídy [SoapHeader](./soapheader/). |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | Klientské proxy služby musí dědit tuto třídu, když se používá SOAP. Objektům této třídy by mělo být přidělováno pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [SoapMessage](./soapmessage/) | Reprezentuje zprávu SOAP. Objektům této třídy by mělo být přidělováno pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [WebClientProtocol](./webclientprotocol/) | Tato základní třída se používá ve všech XML [Web](../system.web/) service client proxy, které byly vytvořeny pomocí ASP.NET. Objektům této třídy by mělo být přidělováno pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
## Výčty

| Výčet | Popis |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | Vyjmenovává směry hlaviček SOAP. |
| [SoapMessageStage](./soapmessagestage/) | Vyjmenovává fáze zpracování zpráv SOAP. |
| [SoapParameterStyle](./soapparameterstyle/) | Vyjmenovává formáty parametrů ve zprávě SOAP. |
| [SoapProtocolVersion](./soapprotocolversion/) | Vyjmenovává verze SOAP. |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | Vyjmenovává možnosti, jak je zpráva SOAP směrována do služby XML [Web](../system.web/). |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [SoapException](./soapexception/) |  |