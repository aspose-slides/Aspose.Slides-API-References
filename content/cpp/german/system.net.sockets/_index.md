---
title: "System::Net::Sockets"
second_title: Aspose.Slides für C++ API Referenz
description: 
type: docs
weight: 729
url: /de/system.net.sockets/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | Stellt die Ausnahme dar, die ausgelöst wird, wenn ein Socket-Fehler auftritt. Erstellen Sie niemals Instanzen dieser Klasse manuell. Verwenden Sie stattdessen die SocketException-Klasse. Wickeln Sie die SocketException-Klasseninstanzen niemals in [System::SmartPtr](../system/smartptr/) ein. |
| [IPPacketInformation](./ippacketinformation/) | Stellt Informationen zum Paket dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [LingerOption](./lingeroption/) | Gibt an, ob ein Socket nach einem Aufruf der Close()- oder Close()-Methoden verbunden bleibt. Sie legt auch den Zeitraum fest, in dem der Socket verbunden bleibt, wenn das Senden der Daten fortgesetzt wird. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [NetworkStream](./networkstream/) | Stellt den zugrunde liegenden Datenstrom für den Netzwerkzugriff bereit. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [Socket](./socket/) | Die Klasse [Socket](./socket/) implementiert die Berkeley-Sockets-Schnittstelle. |
| [TcpClient](./tcpclient/) | Stellt einen Client für die TCP-Netzwerkdienste bereit. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [TcpListener](./tcplistener/) | Stellt einen Listener für die TCP-Netzwerkdienste bereit. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [UdpClient](./udpclient/) | Stellt User Datagram Protocol (UDP)-Netzwerkdienste bereit. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |

## Funktionen

| Funktion | Beschreibung |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |

## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [SocketType](./sockettype/) | Enumeriert die Socket-Typen. |
| [AddressFamily](./addressfamily/) | Enumeriert die Adressfamilien. |
| [IOControlCode](./iocontrolcode/) | Enumeriert die [IO](../system.io/) Steuer-Codes. |
| [ProtocolFamily](./protocolfamily/) | Enumeriert die Protokollfamilien. |
| [ProtocolType](./protocoltype/) | Enumeriert die Protokolltypen. |
| [SelectMode](./selectmode/) | Gibt den Modus für das Abfragen des Socket-Status an. |
| [SocketError](./socketerror/) | Enumeriert die Socket-Fehlertypen. |
| [SocketFlags](./socketflags/) | Stellt konstante Werte für die Socket-Nachrichten bereit. |
| [SocketOptionLevel](./socketoptionlevel/) | Definiert Socket-Optionsebenen für die Klasse '[Socket](./socket/)'. |
| [SocketOptionName](./socketoptionname/) | Definiert Socket-Optionsnamen für die Klasse [Socket](./socket/). |
| [SocketShutdown](./socketshutdown/) | Definiert Konstanten, die von der Methode [Socket.Shutdown](./socket/shutdown/) verwendet werden. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [SocketException](./socketexception/) |  |