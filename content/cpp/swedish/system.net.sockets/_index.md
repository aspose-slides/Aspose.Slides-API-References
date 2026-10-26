---
title: "System::Net::Sockets"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 729
url: /sv/system.net.sockets/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | Representerar undantaget som kastas när ett socket-fel inträffar. Skapa aldrig instanser av den här klassen manuellt. Använd istället klassen SocketException. Omslut aldrig SocketException-klassens instanser i [System::SmartPtr](../system/smartptr/). |
| [IPPacketInformation](./ippacketinformation/) | Representerar information om paketet. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [LingerOption](./lingeroption/) | Anger om en socket ska förbli ansluten efter ett anrop till metoderna Close() eller Close(). Den anger också perioden som socketen förblir ansluten om dataöverföringen fortsätter. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [NetworkStream](./networkstream/) | Tillhandahåller den underliggande strömmen för data för nätverksåtkomst. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [Socket](./socket/) | Klassen [Socket](./socket/) implementerar Berkeley-socket-gränssnittet. |
| [TcpClient](./tcpclient/) | Representerar en klient för TCP-nätverkstjänster. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [TcpListener](./tcplistener/) | Representerar en lyssnare för TCP-nätverkstjänster. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [UdpClient](./udpclient/) | Tillhandahåller User Datagram Protocol (UDP)-nätverkstjänster. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |

## Funktioner

| Funktion | Beskrivning |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |

## Uppräkningar

| Uppräkning | Beskrivning |
| --- | --- |
| [SocketType](./sockettype/) | Enumererar socket-typerna. |
| [AddressFamily](./addressfamily/) | Enumererar adressfamiljerna. |
| [IOControlCode](./iocontrolcode/) | Enumererar [IO](../system.io/)-kontrollkoderna. |
| [ProtocolFamily](./protocolfamily/) | Enumererar protokollfamiljerna. |
| [ProtocolType](./protocoltype/) | Enumererar protokolltyperna. |
| [SelectMode](./selectmode/) | Anger läget för pollning av socketens status. |
| [SocketError](./socketerror/) | Enumererar socket-feltyperna. |
| [SocketFlags](./socketflags/) | Tillhandahåller konstanter för socket-meddelandena. |
| [SocketOptionLevel](./socketoptionlevel/) | Definierar socket-alternativnivåer för klassen '[Socket](./socket/)'. |
| [SocketOptionName](./socketoptionname/) | Definierar socket-alternativnamn för klassen [Socket](./socket/). |
| [SocketShutdown](./socketshutdown/) | Definierar konstanter som används av metoden [Socket.Shutdown](./socket/shutdown/). |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [SocketException](./socketexception/) |  |