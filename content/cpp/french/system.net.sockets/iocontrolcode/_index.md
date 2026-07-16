--- 
title: IOControlCode
second_title: Référence de l'API Aspose.Slides for C++
description: Enumère les codes de contrôle d'E/S.
type: docs
weight: 157
url: /fr/system.net.sockets/iocontrolcode/
---
## IOControlCode enum

Énumère les codes de contrôle [IO](../../system.io/).

```cpp
enum class IOControlCode : int64_t
```

### Values

| Nom | Valeur | Description |
| --- | --- | --- |
| AsyncIO | -2147195267 | Active ou désactive le mode d'E/S asynchrone du socket. |
| NonBlockingIO | -2147195266 | Marque le socket comme non bloquant. |
| DataToRead | 1074030207 | Renvoie le nombre d'octets disponibles pour la lecture. |
| OobDataRead | 1074033415 | Renvoie les informations sur les données hors bande en attente de réception. |
| AssociateHandle | -2013265919 | Associe ce socket au gestionnaire spécifié d'une interface compagnon. |
| EnableCircularQueuing | 671088642 | Remplace le datagramme le plus ancien en file d'attente par un nouveau lorsqu'il n'y a plus de place dans les files d'attente des messages entrants. |
| Flush | 671088644 | Supprime le contenu actuel de la file d'envoi associée à ce socket. |
| GetBroadcastAddress | 1207959557 | Renvoie une structure SOCKADDR contenant l'adresse de diffusion pour la famille d'adresses du socket actuel. |
| GetExtensionFunctionPointer | -939524090 | Récupère un pointeur vers la fonction d'extension spécifiée prise en charge par le fournisseur de services associé. |
| GetQos | -939524089 | Récupère la structure QOS associée au socket. |
| GetGroupQos | -939524088 | Renvoie les attributs QOS pour le groupe de sockets. |
| MultipointLoopback | -2013265911 | Contrôle si les données envoyées par une application sur l'ordinateur local (pas forcément par le même socket) dans une session multicast seront reçues par un socket joint au groupe de destination multicast sur l'interface de bouclage. |
| MulticastScope | -2013265910 | Contrôle le nombre de fois qu'un paquet multicast peut être retransmis par un routeur, également appelé TTL ou compteur de sauts. |
| SetQos | -2013265909 | Définit les attributs QOS pour le socket. |
| SetGroupQos | -2013265908 | Définit les attributs QOS pour le groupe de sockets. |
| TranslateHandle | -939524083 | Renvoie un gestionnaire pour le socket valide dans le contexte d'une interface compagnon. |
| RoutingInterfaceQuery | -939524076 | Renvoie les adresses d'interface pouvant être utilisées pour se connecter à l'adresse distante spécifiée. |
| RoutingInterfaceChange | -2013265899 | Autorise la réception d'une notification lorsque l'interface locale utilisée pour accéder à un point d'extrémité distant change. |
| AddressListQuery | 1207959574 | Renvoie la liste des interfaces locales auxquelles le socket peut se lier. |
| AddressListChange | 671088663 | Autorise la réception d'une notification lorsque la liste des interfaces locales pour la famille de protocole du socket change. |
| QueryTargetPnpHandle | 1207959576 | Récupère le gestionnaire SOCKET du fournisseur sous-jacent. |
| NamespaceChange | -2013265895 | Contrôle si le socket reçoit une notification lorsqu'une requête d'espace de noms devient invalide. |
| AddressListSort | -939524071 | Trie une liste d'adresses de destination IPv6 et IPv4 afin de déterminer la meilleure adresse disponible pour établir une connexion. |
| ReceiveAll | -1744830463 | Autorise la réception de tous les paquets IPv4 sur le réseau. |
| ReceiveAllMulticast | -1744830462 | Autorise la réception de tous les paquets IPv4 multicast sur le réseau. |
| ReceiveAllIgmpMulticast | -1744830461 | Autorise la réception de tous les paquets IGMP sur le réseau. |
| KeepAliveValues | -1744830460 | Contrôle l'envoi de paquets TCP keep-alive et l'intervalle entre les envois. |
| AbsorbRouterAlert | -1744830459 | Cette valeur est égale à la constante Winsock 2 'SIO_ABSORB_RTRALERT'. |
| UnicastInterface | -1744830458 | Définit l'interface utilisée pour les paquets unicast sortants. |
| LimitBroadcasts | -1744830457 | Cette valeur est égale à la constante Winsock 2 'SIO_LIMIT_BROADCASTS'. |
| BindToInterface | -1744830456 | Assigne le socket à l'index d'interface spécifié. |
| MulticastInterface | -1744830455 | Définit l'interface utilisée pour les paquets multicast sortants. |
| AddMulticastGroupOnInterface | -1744830454 | Rejoint un groupe multicast en utilisant une interface identifiée par son index. |
| DeleteMulticastGroupFromInterface | -1744830453 | Retire le socket d'un groupe multicast. |

## Voir aussi

* Espace de noms [System::Net::Sockets](../)
* Bibliothèque [Aspose.Slides](../../)