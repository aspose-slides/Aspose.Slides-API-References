---
title: "System::Net::Sockets"
second_title: Aspose.Slides dla C++ – dokumentacja API
description: 
type: docs
weight: 729
url: /pl/system.net.sockets/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | Reprezentuje wyjątek zgłaszany, gdy wystąpi błąd gniazda. Nigdy nie twórz ręcznie instancji tej klasy. Użyj klasy SocketException. Nigdy nie opakowuj instancji klasy SocketException w [System::SmartPtr](../system/smartptr/). |
| [IPPacketInformation](./ippacketinformation/) | Reprezentuje informacje o pakiecie. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę we wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [LingerOption](./lingeroption/) | Określa, czy socket pozostanie połączony po wywołaniu metod Close() lub Close(). Określa również okres, przez który socket pozostanie połączony, jeśli transmisja danych będzie kontynuowana. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę we wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [NetworkStream](./networkstream/) | Dostarcza podstawowy strumień danych dla dostępu sieciowego. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę we wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [Socket](./socket/) | Klasa [Socket](./socket/) implementuje interfejs gniazd Berkeley. |
| [TcpClient](./tcpclient/) | Reprezentuje klienta usług sieciowych TCP. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę we wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [TcpListener](./tcplistener/) | Reprezentuje nasłuchującego usług sieciowych TCP. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę we wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [UdpClient](./udpclient/) | Dostarcza usługi protokołu UDP. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę we wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |

## Funkcje

| Funkcja | Opis |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |

## Wyliczenia

| Wyliczenie | Opis |
| --- | --- |
| [SocketType](./sockettype/) | Enumeruje typy gniazd. |
| [AddressFamily](./addressfamily/) | Enumeruje rodziny adresów. |
| [IOControlCode](./iocontrolcode/) | Enumeruje kody sterujące [IO](../system.io/). |
| [ProtocolFamily](./protocolfamily/) | Enumeruje rodziny protokołów. |
| [ProtocolType](./protocoltype/) | Enumeruje typy protokołów. |
| [SelectMode](./selectmode/) | Określa tryb sondowania statusu gniazda. |
| [SocketError](./socketerror/) | Enumeruje typy błędów gniazd. |
| [SocketFlags](./socketflags/) | Dostarcza stałe wartości dla komunikatów gniazda. |
| [SocketOptionLevel](./socketoptionlevel/) | Definiuje poziomy opcji gniazda dla klasy '[Socket](./socket/)'. |
| [SocketOptionName](./socketoptionname/) | Definiuje nazwy opcji gniazda dla klasy [Socket](./socket/). |
| [SocketShutdown](./socketshutdown/) | Definiuje stałe używane przez metodę [Socket.Shutdown](./socket/shutdown/). |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [SocketException](./socketexception/) |  |