---
title: IOControlCode
second_title: Aspose.Slides för C++ API-referens
description: Enumererar IO-kontrollkoderna.
type: docs
weight: 157
url: /sv/system.net.sockets/iocontrolcode/
---
## IOControlCode enum

Enumererar [IO](../../system.io/) kontrollkoder.

```cpp
enum class IOControlCode : int64_t
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| AsyncIO | -2147195267 | Aktivera eller inaktivera det asynkrona I/O-läget för socketen. |
| NonBlockingIO | -2147195266 | Markera socketen som icke-blockerande. |
| DataToRead | 1074030207 | Returnerar antalet byte som är tillgängliga för läsning. |
| OobDataRead | 1074033415 | Returnerar information om out-of-band-data som väntar på att tas emot. |
| AssociateHandle | -2013265919 | Associera denna socket med den specificerade handle för ett medföljande gränssnitt. |
| EnableCircularQueuing | 671088642 | Ersätt den äldsta köade datagrammen med en inkommande när de inkommande meddelandeköerna är fulla. |
| Flush | 671088644 | Kastar bort aktuellt innehåll i sändningskön som är associerad med denna socket. |
| GetBroadcastAddress | 1207959557 | Returnerar en SOCKADDR-struktur som innehåller broadcast-adressen för adressfamiljen för den aktuella socketen. |
| GetExtensionFunctionPointer | -939524090 | Hämtar en pekare till den specificerade extension-funktionen som stöds av den associerade service provider. |
| GetQos | -939524089 | Hämtar QOS-strukturen som är associerad med socketen. |
| GetGroupQos | -939524088 | Returnerar QOS-attributen för socket-gruppen. |
| MultipointLoopback | -2013265911 | Styr om data som skickas av ett program på den lokala datorn (inte nödvändigtvis av samma socket) i en multicast-session ska tas emot av en socket som är ansluten till multicast-destinationsgruppen på loopback-gränssnittet. |
| MulticastScope | -2013265910 | Styr hur många gånger ett multicast-paket kan vidarebefordras av en router, även känt som TTL eller hoppantal. |
| SetQos | -2013265909 | Ställer in QOS-attributen för socketen. |
| SetGroupQos | -2013265908 | Ställer in QOS-attributen för socket-gruppen. |
| TranslateHandle | -939524083 | Returnerar ett handle för socketen som är giltigt i samband med ett medföljande gränssnitt. |
| RoutingInterfaceQuery | -939524076 | Returnerar gränssnittsadresserna som kan användas för att ansluta till den specificerade fjärradressen. |
| RoutingInterfaceChange | -2013265899 | Aktivera mottagning av en notifikation när det lokala gränssnittet som används för att nå en fjärrändpunkt ändras. |
| AddressListQuery | 1207959574 | Returnerar listan över de lokala gränssnitten som socketen kan bindas till. |
| AddressListChange | 671088663 | Aktivera mottagning av en notifikation när listan över de lokala gränssnitten för socketens protokollfamilj ändras. |
| QueryTargetPnpHandle | 1207959576 | Hämtar den underliggande leverantörens SOCKET-handle. |
| NamespaceChange | -2013265895 | Styr om socketen får en notifikation när en namnrymdsfråga blir ogiltig. |
| AddressListSort | -939524071 | Sortera en lista med IPv6- och IPv4-destinationsadresser för att avgöra den bästa tillgängliga adressen för att skapa en anslutning. |
| ReceiveAll | -1744830463 | Aktivera mottagning av alla IPv4-paket på nätverket. |
| ReceiveAllMulticast | -1744830462 | Aktivera mottagning av alla multicast-IPv4-paket på nätverket. |
| ReceiveAllIgmpMulticast | -1744830461 | Aktivera mottagning av alla IGMP-paket på nätverket. |
| KeepAliveValues | -1744830460 | Styr sändning av TCP keep-alive-paket och intervallet mellan dem. |
| AbsorbRouterAlert | -1744830459 | Detta värde är lika med Winsock 2-konstanten 'SIO_ABSORB_RTRALERT'. |
| UnicastInterface | -1744830458 | Ställer in gränssnittet som används för utgående unicast-paket. |
| LimitBroadcasts | -1744830457 | Detta värde är lika med Winsock 2-konstanten 'SIO_LIMIT_BROADCASTS'. |
| BindToInterface | -1744830456 | Bind socketen till ett specificerat gränssnittsindex. |
| MulticastInterface | -1744830455 | Ställer in gränssnittet som används för utgående multicast-paket. |
| AddMulticastGroupOnInterface | -1744830454 | Gå med i en multicast-grupp med ett gränssnitt identifierat av dess index. |
| DeleteMulticastGroupFromInterface | -1744830453 | Ta bort socketen från en multicast-grupp. |

## Se även

* Namnrymd [System::Net::Sockets](../)
* Bibliotek [Aspose.Slides](../../)