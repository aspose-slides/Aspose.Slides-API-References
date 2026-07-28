---
title: "System::Web::Services::Protocols"
second_title: Aspose.Slides dla C++ – dokumentacja API
description: 
type: docs
weight: 1080
url: /pl/system.web.services.protocols/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | Reprezentuje wyjątek zgłaszany, gdy metoda jest wywoływana przez SOAP i występuje błąd. Nigdy nie twórz ręcznie instancji tej klasy. Zamiast tego użyj klasy SoapException. Nigdy nie umieszczaj instancji klasy SoapException w [System::SmartPtr](../system/smartptr/). |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | Ta klasa bazowa jest używana we wszystkich klientach proxy usług XML [Web](../system.web/) wykorzystujących protokół HTTP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | Instancja tej klasy jest przekazywana jako argument do delegata InvokeCompletedEventHandler. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu. |
| [SoapClientMessage](./soapclientmessage/) | Reprezentuje dane w wysyłanym żądaniu SOAP lub otrzymanej odpowiedzi SOAP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | Określa, że wszystkie komunikaty SOAP przekazywane lub zwracane przez metodę używają formatowania Document. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | Ustawia domyślny format dla żądań i odpowiedzi SOAP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu. |
| [SoapHeader](./soapheader/) | Reprezentuje zawartość nagłówka SOAP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu. |
| [SoapHeaderAttribute](./soapheaderattribute/) | Określa nagłówek SOAP, który metoda usługi XML [Web](../system.web/) lub klient usługi XML [Web](../system.web/) może przetworzyć. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu. |
| [SoapHeaderCollection](./soapheadercollection/) | Zawiera kolekcję instancji klasy [SoapHeader](./soapheader/). |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | Usługi proxy klienta muszą dziedziczyć tę klasę, gdy używany jest SOAP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu. |
| [SoapMessage](./soapmessage/) | Reprezentuje komunikat SOAP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu. |
| [WebClientProtocol](./webclientprotocol/) | Ta klasa bazowa jest używana we wszystkich klientach proxy usług XML [Web](../system.web/) utworzonych przy użyciu ASP.NET. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu. |

## Wyliczenia

| Wyliczenie | Opis |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | Wymienia kierunki nagłówka SOAP. |
| [SoapMessageStage](./soapmessagestage/) | Wymienia etapy przetwarzania komunikatów SOAP. |
| [SoapParameterStyle](./soapparameterstyle/) | Wymienia formaty parametrów w komunikacie SOAP. |
| [SoapProtocolVersion](./soapprotocolversion/) | Wymienia wersje SOAP. |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | Wymienia opcje dotyczące routingu komunikatu SOAP do usługi XML [Web](../system.web/). |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [SoapException](./soapexception/) |  |