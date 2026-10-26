---
title: "System::Net::Sockets"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 729
url: /nl/system.net.sockets/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | Representeert de uitzondering die wordt gegooid wanneer er een socket-fout optreedt. Maak nooit handmatig exemplaren van deze klasse aan. Gebruik in plaats daarvan de SocketException-klasse. Verpak de SocketException-klassenexemplaren nooit in [System::SmartPtr](../system/smartptr/). |
| [IPPacketInformation](./ippacketinformation/) | Representeert informatie over het pakket. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie [System::MakeObject()](../system/makeobject/). Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [LingerOption](./lingeroption/) | Bepaalt of een socket verbonden blijft na een aanroep van de Close()- of Close()-methoden. Het specificeert ook de periode waarin de socket verbonden blijft als het verzenden van gegevens doorgaat. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie [System::MakeObject()](../system/makeobject/). Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [NetworkStream](./networkstream/) | Levert de onderliggende gegevensstroom voor netwerktoegang. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie [System::MakeObject()](../system/makeobject/). Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [Socket](./socket/) | De [Socket](./socket/) klasse implementeert de Berkeley sockets-interface. |
| [TcpClient](./tcpclient/) | Representeert een client voor de TCP-netwerkservices. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie [System::MakeObject()](../system/makeobject/). Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [TcpListener](./tcplistener/) | Representeert een luisteraar voor de TCP-netwerkservices. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie [System::MakeObject()](../system/makeobject/). Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [UdpClient](./udpclient/) | Levert User Datagram Protocol (UDP) netwerkservices. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie [System::MakeObject()](../system/makeobject/). Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |

## Functies

| Functie | Beschrijving |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |

## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [SocketType](./sockettype/) | Enumereert de socket-types. |
| [AddressFamily](./addressfamily/) | Enumereert de adresfamilies. |
| [IOControlCode](./iocontrolcode/) | Enumereert de [IO](../system.io/) besturingscodes. |
| [ProtocolFamily](./protocolfamily/) | Enumereert de protocolfamilies. |
| [ProtocolType](./protocoltype/) | Enumereert de protocoltypen. |
| [SelectMode](./selectmode/) | Bepaalt de modus voor het poll-en van de socketstatus. |
| [SocketError](./socketerror/) | Enumereert de socket-fouttypes. |
| [SocketFlags](./socketflags/) | Levert constante waarden voor de socket-berichten. |
| [SocketOptionLevel](./socketoptionlevel/) | Bepaalt socket-optieniveaus voor de '[Socket](./socket/)' klasse. |
| [SocketOptionName](./socketoptionname/) | Bepaalt socket-optienamen voor de [Socket](./socket/) klasse. |
| [SocketShutdown](./socketshutdown/) | Bepaalt constanten die gebruikt worden door de [Socket.Shutdown](./socket/shutdown/)-methode. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [SocketException](./socketexception/) |  |