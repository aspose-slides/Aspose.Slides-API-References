---
title: "System::Net::Sockets"
second_title: Référence API Aspose.Slides pour C++
description: 
type: docs
weight: 729
url: /fr/system.net.sockets/
---
## Classes

| Classe | Description |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | Représente l'exception levée lorsqu'une erreur de socket se produit. Ne créez jamais d'instances de cette classe manuellement. Utilisez la classe SocketException à la place. Ne regroupez jamais les instances de la classe SocketException dans [System::SmartPtr](../system/smartptr/). |
| [IPPacketInformation](./ippacketinformation/) | Représente les informations sur le paquet. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défaillances d'assertion. Encapsulez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [LingerOption](./lingeroption/) | Spécifie si un socket restera connecté après un appel aux méthodes Close() ou Close(). Il spécifie également la durée pendant laquelle le socket restera connecté si l'envoi des données se poursuit. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défaillances d'assertion. Encapsulez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [NetworkStream](./networkstream/) | Fournit le flux sous-jacent des données pour l'accès réseau. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défaillances d'assertion. Encapsulez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [Socket](./socket/) | La classe [Socket](./socket/) implémente l'interface de sockets Berkeley. |
| [TcpClient](./tcpclient/) | Représente un client pour les services réseau TCP. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défaillances d'assertion. Encapsulez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [TcpListener](./tcplistener/) | Représente un écouteur pour les services réseau TCP. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défaillances d'assertion. Encapsulez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [UdpClient](./udpclient/) | Fournit les services réseau User Datagram Protocol (UDP). Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défaillances d'assertion. Encapsulez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |

## Fonctions

| Fonction | Description |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) | |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) | |

## Énumérations

| Enumération | Description |
| --- | --- |
| [SocketType](./sockettype/) | Énumère les types de sockets. |
| [AddressFamily](./addressfamily/) | Énumère les familles d'adresses. |
| [IOControlCode](./iocontrolcode/) | Énumère les codes de contrôle [IO](../system.io/). |
| [ProtocolFamily](./protocolfamily/) | Énumère les familles de protocoles. |
| [ProtocolType](./protocoltype/) | Énumère les types de protocoles. |
| [SelectMode](./selectmode/) | Spécifie le mode de sondage de l'état du socket. |
| [SocketError](./socketerror/) | Énumère les types d'erreurs de socket. |
| [SocketFlags](./socketflags/) | Fournit des valeurs constantes pour les messages de socket. |
| [SocketOptionLevel](./socketoptionlevel/) | Définit les niveaux d'options de socket pour la classe '[Socket](./socket/)'. |
| [SocketOptionName](./socketoptionname/) | Définit les noms d'options de socket pour la classe [Socket](./socket/). |
| [SocketShutdown](./socketshutdown/) | Définit les constantes utilisées par la méthode [Socket.Shutdown](./socket/shutdown/). |

## Définitions de type

| Définition de type | Description |
| --- | --- |
| [SocketException](./socketexception/) |  |