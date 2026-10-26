---
title: IOControlCode
second_title: Aspose.Slides voor C++ API-referentie
description: Enumereert de IO-besturingscodes.
type: docs
weight: 157
url: /nl/system.net.sockets/iocontrolcode/
---
## IOControlCode enum


Enumereert de [IO](../../system.io/) besturingscodes.

```cpp
enum class IOControlCode : int64_t
```

### Values

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| AsyncIO | -2147195267 | Schakel de asynchrone I/O-modus van de socket in of uit. |
| NonBlockingIO | -2147195266 | Markeer de socket als niet-blokkerend. |
| DataToRead | 1074030207 | Retourneer het aantal bytes dat beschikbaar is voor lezen. |
| OobDataRead | 1074033415 | Retourneer informatie over out-of-band-gegevens die wachten om ontvangen te worden. |
| AssociateHandle | -2013265919 | Koppel deze socket aan de opgegeven handle van een companion interface. |
| EnableCircularQueuing | 671088642 | Vervang het oudste in de wachtrij staande datagram door een nieuw binnenkomend wanneer de binnenkomende berichtwachtrijen vol zijn. |
| Flush | 671088644 | Verwijdert de huidige inhoud van de verzendwachtrij die aan deze socket is gekoppeld. |
| GetBroadcastAddress | 1207959557 | Retourneer een SOCKADDR-structuur die het broadcastadres bevat voor de adresfamilie van de huidige socket. |
| GetExtensionFunctionPointer | -939524090 | Haalt een pointer op naar de opgegeven extensiefunctie die wordt ondersteund door de gekoppelde serviceprovider. |
| GetQos | -939524089 | Haalt de QOS-structuur op die aan de socket is gekoppeld. |
| GetGroupQos | -939524088 | Retourneer de QOS-attributen voor de socketgroep. |
| MultipointLoopback | -2013265911 | Bepaal of gegevens die door een toepassing op de lokale computer (niet noodzakelijkerwijs via dezelfde socket) in een multicast-sessie worden verzonden, worden ontvangen door een socket die is aangesloten op de multicast-doelgroep op de loopback-interface. |
| MulticastScope | -2013265910 | Bepaal het aantal keren dat een multicast-pakket door een router mag worden doorgestuurd, ook wel TTL of hop-count genoemd. |
| SetQos | -2013265909 | Stel de QOS-attributen in voor de socket. |
| SetGroupQos | -2013265908 | Stel de QOS-attributen in voor de socketgroep. |
| TranslateHandle | -939524083 | Retourneer een handle voor de socket die geldig is in de context van een companion interface. |
| RoutingInterfaceQuery | -939524076 | Retourneer de interface-adressen die kunnen worden gebruikt om verbinding te maken met het opgegeven externe adres. |
| RoutingInterfaceChange | -2013265899 | Schakel het ontvangen van een melding in wanneer de lokale interface die wordt gebruikt om een extern eindpunt te benaderen verandert. |
| AddressListQuery | 1207959574 | Retourneer de lijst van de lokale interfaces waaraan de socket kan binden. |
| AddressListChange | 671088663 | Schakel het ontvangen van een melding in wanneer de lijst van lokale interfaces voor de protocolfamilie van de socket verandert. |
| QueryTargetPnpHandle | 1207959576 | Haalt de onderliggende provider-SOCKET-handle op. |
| NamespaceChange | -2013265895 | Bepaal of de socket een melding ontvangt wanneer een namespace-query ongeldig wordt. |
| AddressListSort | -939524071 | Sorteer een lijst van IPv6- en IPv4-bestemmingsadressen om het best beschikbare adres voor het tot stand brengen van een verbinding te bepalen. |
| ReceiveAll | -1744830463 | Schakel het ontvangen van alle IPv4-pakketten op het netwerk in. |
| ReceiveAllMulticast | -1744830462 | Schakel het ontvangen van alle multicast-IPv4-pakketten op het netwerk in. |
| ReceiveAllIgmpMulticast | -1744830461 | Schakel het ontvangen van alle IGMP-pakketten op het netwerk in. |
| KeepAliveValues | -1744830460 | Bepaal het verzenden van TCP-keep-alive-pakketten en het interval waarop ze worden verzonden. |
| AbsorbRouterAlert | -1744830459 | Deze waarde is gelijk aan de Winsock 2-constante 'SIO_ABSORB_RTRALERT'. |
| UnicastInterface | -1744830458 | Stel de interface in die wordt gebruikt voor uitgaande unicast-pakketten. |
| LimitBroadcasts | -1744830457 | Deze waarde is gelijk aan de Winsock 2-constante 'SIO_LIMIT_BROADCASTS'. |
| BindToInterface | -1744830456 | Koppel de socket aan een opgegeven interface-index. |
| MulticastInterface | -1744830455 | Stel de interface in die wordt gebruikt voor uitgaande multicast-pakketten. |
| AddMulticastGroupOnInterface | -1744830454 | Word lid van een multicast-groep via een interface die wordt geïdentificeerd door zijn index. |
| DeleteMulticastGroupFromInterface | -1744830453 | Verwijder de socket uit een multicast-groep. |

## Zie ook

* Namespace [System::Net::Sockets](../)
* Library [Aspose.Slides](../../)