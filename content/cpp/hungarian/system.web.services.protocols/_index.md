---
title: "System::Web::Services::Protocols"
second_title: Aspose.Slides for C++ API-referencia
description: 
type: docs
weight: 1080
url: /hu/system.web.services.protocols/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | Azon kivételt reprezentálja, amely akkor dobódik, amikor a metódust SOAP-on keresztül hívják, és hiba lép fel. Soha ne hozzon létre példányokat ebből az osztályból manuálisan. Használja helyette a SoapException osztályt. Soha ne csomagolja a SoapException osztály példányait a [System::SmartPtr](../system/smartptr/)-be. |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | Ez az alaposztály minden HTTP-t használó XML [Web](../system.web/) szolgáltatás kliens proxyban használatos. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként függvényeknek való átadáshoz. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | Az osztály egy példányát argumentumként adják át az InvokeCompletedEventHandler delegátornak. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként függvényeknek való átadáshoz. |
| [SoapClientMessage](./soapclientmessage/) | A SOAP kérésben elküldött vagy a SOAP válaszban kapott adatokat reprezentálja. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként függvényeknek való átadáshoz. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | Meghatározza, hogy minden, a metódusról átadott vagy visszakapott SOAP üzenet a Document formázást használja. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként függvényeknek való átadáshoz. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | Beállítja a SOAP kérések és válaszok alapértelmezett formátumát. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként függvényeknek való átadáshoz. |
| [SoapHeader](./soapheader/) | A SOAP fejléc tartalmát reprezentálja. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként függvényeknek való átadáshoz. |
| [SoapHeaderAttribute](./soapheaderattribute/) | Meghatározza a SOAP fejlécet, amelyet az XML [Web](../system.web/) szolgáltatás metódusa vagy az XML [Web](../system.web/) szolgáltatás kliensje képes feldolgozni. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként függvényeknek való átadáshoz. |
| [SoapHeaderCollection](./soapheadercollection/) | Tartalmazza a [SoapHeader](./soapheader/) osztály példányainak gyűjteményét. |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | A kliens proxy szolgáltatásoknak örökölniük kell ezt az osztályt, amikor a SOAP-t használják. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként függvényeknek való átadáshoz. |
| [SoapMessage](./soapmessage/) | A SOAP üzenetet reprezentálja. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként függvényeknek való átadáshoz. |
| [WebClientProtocol](./webclientprotocol/) | Ez az alaposztály minden ASP.NET-kel létrehozott XML [Web](../system.web/) szolgáltatás kliens proxyban használatos. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként függvényeknek való átadáshoz. |
## Enumok

| Enum | Leírás |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | A SOAP fejléc irányait sorolja fel. |
| [SoapMessageStage](./soapmessagestage/) | A SOAP üzenetek feldolgozási szakaszait sorolja fel. |
| [SoapParameterStyle](./soapparameterstyle/) | A SOAP üzenetben szereplő paraméterformátumokat sorolja fel. |
| [SoapProtocolVersion](./soapprotocolversion/) | A SOAP verzióit sorolja fel. |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | A SOAP üzenet XML [Web](../system.web/) szolgáltatáshoz való irányításának lehetőségeit sorolja fel. |
## Typedef-ek

| Typedef | Leírás |
| --- | --- |
| [SoapException](./soapexception/) |  |