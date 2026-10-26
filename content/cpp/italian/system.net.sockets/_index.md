---
title: "System::Net::Sockets"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 729
url: /it/system.net.sockets/
---
## Classi

| Class | Descrizione |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | Rappresenta l'eccezione generata quando si verifica un errore di socket. Non creare istanze di questa classe manualmente. Usa invece la classe SocketException. Non avvolgere mai le istanze della classe SocketException in [System::SmartPtr](../system/smartptr/). |
| [IPPacketInformation](./ippacketinformation/) | Rappresenta le informazioni sul pacchetto. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento. |
| [LingerOption](./lingeroption/) | Specifica se un socket rimarrà connesso dopo una chiamata ai metodi Close() o Close(). Specifica anche il periodo durante il quale il socket rimarrà connesso se la trasmissione dei dati continua. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento. |
| [NetworkStream](./networkstream/) | Fornisce lo stream sottostante dei dati per l'accesso di rete. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza questo puntatore per passarla alle funzioni come argomento. |
| [Socket](./socket/) | La classe [Socket](./socket/) implementa l'interfaccia Berkeley sockets. |
| [TcpClient](./tcpclient/) | Rappresenta un client per i servizi di rete TCP. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento. |
| [TcpListener](./tcplistener/) | Rappresenta un listener per i servizi di rete TCP. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento. |
| [UdpClient](./udpclient/) | Fornisce i servizi di rete User Datagram Protocol (UDP). Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento. |

## Funzioni

| Function | Descrizione |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |

## Enumerazioni

| Enumerazione | Descrizione |
| --- | --- |
| [SocketType](./sockettype/) | Elenca i tipi di socket. |
| [AddressFamily](./addressfamily/) | Elenca le famiglie di indirizzi. |
| [IOControlCode](./iocontrolcode/) | Elenca i codici di controllo [IO](../system.io/). |
| [ProtocolFamily](./protocolfamily/) | Elenca le famiglie di protocolli. |
| [ProtocolType](./protocoltype/) | Elenca i tipi di protocollo. |
| [SelectMode](./selectmode/) | Specifica la modalità per il polling dello stato del socket. |
| [SocketError](./socketerror/) | Elenca i tipi di errore del socket. |
| [SocketFlags](./socketflags/) | Fornisce valori costanti per i messaggi del socket. |
| [SocketOptionLevel](./socketoptionlevel/) | Definisce i livelli delle opzioni socket per la classe '[Socket](./socket/)'. |
| [SocketOptionName](./socketoptionname/) | Definisce i nomi delle opzioni socket per la classe [Socket](./socket/). |
| [SocketShutdown](./socketshutdown/) | Definisce le costanti utilizzate dal metodo [Socket.Shutdown](./socket/shutdown/). |

## Alias di tipo

| Alias | Descrizione |
| --- | --- |
| [SocketException](./socketexception/) |  |