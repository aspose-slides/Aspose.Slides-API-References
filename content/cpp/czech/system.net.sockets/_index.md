---
title: "System::Net::Sockets"
second_title: Aspose.Slides pro C++ - referenční příručka API
description: 
type: docs
weight: 729
url: /cs/system.net.sockets/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | Representuje výjimku vyhozenou při výskytu chyby socketu. Nikdy nevytvářejte instance této třídy ručně. Místo toho použijte třídu SocketException. Nikdy neobalujte instance třídy SocketException do [System::SmartPtr](../system/smartptr/). |
| [IPPacketInformation](./ippacketinformation/) | Representuje informace o paketu. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [LingerOption](./lingeroption/) | Udává, zda socket zůstane připojen po volání metod Close() nebo Close(). Také udává dobu, po kterou bude socket připojen, pokud bude pokračovat odesílání dat. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [NetworkStream](./networkstream/) | Poskytuje podkladový stream dat pro síťový přístup. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [Socket](./socket/) | Třída [Socket](./socket/) implementuje rozhraní Berkeley sockets. |
| [TcpClient](./tcpclient/) | Representuje klienta pro služby TCP sítí. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [TcpListener](./tcplistener/) | Representuje posluchače pro služby TCP sítí. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [UdpClient](./udpclient/) | Poskytuje služby User Datagram Protocol (UDP). Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
## Funkce

| Funkce | Popis |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
## Výčty

| Výčet | Popis |
| --- | --- |
| [SocketType](./sockettype/) | Vyjmenovává typy socketů. |
| [AddressFamily](./addressfamily/) | Vyjmenovává rodiny adres. |
| [IOControlCode](./iocontrolcode/) | Vyjmenovává řídicí kódy [IO](../system.io/). |
| [ProtocolFamily](./protocolfamily/) | Vyjmenovává rodiny protokolů. |
| [ProtocolType](./protocoltype/) | Vyjmenovává typy protokolů. |
| [SelectMode](./selectmode/) | Určuje režim pro dotazování stavu socketu. |
| [SocketError](./socketerror/) | Vyjmenovává typy chyb socketu. |
| [SocketFlags](./socketflags/) | Poskytuje konstantní hodnoty pro zprávy socketu. |
| [SocketOptionLevel](./socketoptionlevel/) | Definuje úrovně možností socketu pro třídu '[Socket](./socket/)'. |
| [SocketOptionName](./socketoptionname/) | Definuje názvy možností socketu pro třídu [Socket](./socket/). |
| [SocketShutdown](./socketshutdown/) | Definuje konstanty používané metodou [Socket.Shutdown](./socket/shutdown/). |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [SocketException](./socketexception/) |  |