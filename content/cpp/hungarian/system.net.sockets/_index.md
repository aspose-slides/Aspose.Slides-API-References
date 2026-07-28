---
title: "System::Net::Sockets"
second_title: "Aspose.Slides C++ API-referencia"
description: 
type: docs
weight: 729
url: /hu/system.net.sockets/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | Képviseli azt a kivételt, amelyet akkor dob a rendszer, ha socket hiba lép fel. Soha ne hozzon létre példányokat ebből az osztályból kézzel. Használja a SocketException osztályt helyette. Soha ne csomagolja a SocketException osztály példányait a [System::SmartPtr](../system/smartptr/)-ba. |
| [IPPacketInformation](./ippacketinformation/) | Képviseli a csomagról szóló információkat. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek. |
| [LingerOption](./lingeroption/) | Megadja, hogy egy socket a Close() vagy Close() metódus hívása után tovább marad-e csatlakoztatva. Emellett meghatározza azt az időszakot, ameddig a socket csatlakoztatva marad, ha az adatküldés folytatódik. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek. |
| [NetworkStream](./networkstream/) | Biztosítja a hálózati hozzáféréshez szükséges adatok alapvető adatfolyamát. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek. |
| [Socket](./socket/) | A [Socket](./socket/) osztály a Berkeley socketek interfészét valósítja meg. |
| [TcpClient](./tcpclient/) | Képviseli a TCP hálózati szolgáltatások kliensét. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek. |
| [TcpListener](./tcplistener/) | Képviseli a TCP hálózati szolgáltatások hallgatóját. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek. |
| [UdpClient](./udpclient/) | Biztosítja a User Datagram Protocol (UDP) hálózati szolgáltatásait. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek. |

## Függvények

| Függvény | Leírás |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |

## Enumerációk

| Enumeráció | Leírás |
| --- | --- |
| [SocketType](./sockettype/) | Felsorolja a socket típusokat. |
| [AddressFamily](./addressfamily/) | Felsorolja a cím családokat. |
| [IOControlCode](./iocontrolcode/) | Felsorolja a [IO](../system.io/) vezérlőkódokat. |
| [ProtocolFamily](./protocolfamily/) | Felsorolja a protokollcsaládokat. |
| [ProtocolType](./protocoltype/) | Felsorolja a protokoll típusokat. |
| [SelectMode](./selectmode/) | Megadja a módot a socket állapotának lekérdezésére. |
| [SocketError](./socketerror/) | Felsorolja a socket hiba típusokat. |
| [SocketFlags](./socketflags/) | Állandó értékeket biztosít a socket üzenetekhez. |
| [SocketOptionLevel](./socketoptionlevel/) | Meghatározza a socket opció szinteket a '[Socket](./socket/)' osztályhoz. |
| [SocketOptionName](./socketoptionname/) | Meghatározza a socket opció neveket a [Socket](./socket/) osztályhoz. |
| [SocketShutdown](./socketshutdown/) | Meghatározza a [Socket.Shutdown](./socket/shutdown/) metódus által használt állandókat. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [SocketException](./socketexception/) |  |