---
title: "System::Net::Http"
second_title: Aspose.Slides dla C++ – Referencja API
description: 
type: docs
weight: 677
url: /pl/system.net.http/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | Reprezentuje zawartość HTTP jako tablicę bajtów. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub naruszenia asercji. Zawsze owijaj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [Details_HttpRequestException](./details_httprequestexception/) | Klasa bazowa wyjątków jest rzucana przez klasy [HttpClient](./httpclient/) i [HttpMessageHandler](./httpmessagehandler/). Nigdy nie twórz ręcznie instancji tej klasy. Użyj zamiast tego klasy HttpRequestException. Nigdy nie owijaj instancji klasy HttpRequestException w [System::SmartPtr](../system/smartptr/). |
| [HttpClient](./httpclient/) | Reprezentuje klasę bazową klienta HTTP służącą do wysyłania żądań i odbierania odpowiedzi. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub naruszenia asercji. Zawsze owijaj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [HttpClientHandler](./httpclienthandler/) | Reprezentuje domyślny obsługujący wiadomości używany przez klasę [HttpClient](./httpclient/). Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub naruszenia asercji. Zawsze owijaj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [HttpContent](./httpcontent/) | Reprezentuje zawartość jednostki HTTP. [Object](../system/object/) tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub naruszenia asercji. Zawsze owijaj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [HttpMessageHandler](./httpmessagehandler/) | Reprezentuje bazowy typ dla obsługujących wiadomości HTTP. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub naruszenia asercji. Zawsze owijaj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [HttpMessageInvoker](./httpmessageinvoker/) | Umożliwia aplikacjom wywoływanie metody Send w łańcuchu obsługi HTTP. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub naruszenia asercji. Zawsze owijaj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [HttpMethod](./httpmethod/) | Reprezentuje metodę HTTP. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub naruszenia asercji. Zawsze owijaj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [HttpRequestMessage](./httprequestmessage/) | Reprezentuje wiadomość żądania HTTP. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub naruszenia asercji. Zawsze owijaj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [HttpResponseMessage](./httpresponsemessage/) | Reprezentuje wiadomość odpowiedzi HTTP. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub naruszenia asercji. Zawsze owijaj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [HttpUtilities](./httputilities/) | Zawiera metody pomocnicze. |
| [StringContent](./stringcontent/) | Reprezentuje zawartość HTTP jako ciąg znaków. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub naruszenia asercji. Zawsze owijaj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |

## Funkcje

| Funkcja | Opis |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |

## Wyliczenia

| Wyliczenie | Opis |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | Wskazuje, kiedy operacja [HttpClient](./httpclient/) powinna zostać zakończona. |
| [HttpParseResult](./httpparseresult/) | Wskazuje wynik parsowania. |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |