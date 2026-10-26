---
title: SocketOptionName
second_title: Aspose.Slides för C++ API-referens
description: Definierar namn på socketalternativ för Socket-klassen.
type: docs
weight: 248
url: /sv/system.net.sockets/socketoptionname/
---
## SocketOptionName enum

Definierar socket-alternativnamn för klassen [Socket](../socket/).

```cpp
enum class SocketOptionName
```

### Values

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Debug | 1 | Spela in felsökningsinformation. |
| AcceptConnection | 2 | Anger om en socket lyssnar på en inkommande anslutning. |
| ReuseAddress | 4 | Anger om en socket kan bindas till en adress som redan är i bruk. |
| KeepAlive | 8 | Aktiverar 'Keep-Alive'-paket för en socketanslutning. |
| DontRoute | 16 | Anger om ett paket skickas direkt till gränssnittets adresser. |
| Broadcast | 32 | Anger om en socket kan skicka broadcast-meddelanden. |
| UseLoopback | 64 | Förbigå hårdvara när det är möjligt. |
| Linger | 128 | Systemet kommer blockera processen vid stängningsförsöket tills den kan överföra data. |
| OutOfBandInline | 256 | Tar emot out-of-band-data i den normala dataströmmen. |
| DontLinger | n/a | Anger om en socket kommer att stängas utan fördröjning. |
| ExclusiveAddressUse | n/a | En socket kommer att använda den bundna adressen exklusivt. |
| SendBuffer | 4097 | Anger storleken på sändningsbufferten. |
| ReceiveBuffer | 4098 | Anger storleken på mottagningsbufferten. |
| SendLowWater | 4099 | Anger den minsta datamängden för sändningsoperationer. |
| ReceiveLowWater | 4100 | Anger den minsta datamängden för mottagningsoperationer. |
| SendTimeout | 4101 | Anger tidsgränsen för synkrona sändningsoperationer. |
| ReceiveTimeout | 4102 | Anger tidsgränsen för synkrona mottagningsoperationer. |
| Error | 4103 | Returnerar felstatusen och rensar. |
| Type | 4104 | Returnerar en sockets typ. |
| ReuseUnicastPort | 12295 | Anger om systemet ska fördröja den tillfälliga portallokeringen för utgående anslutningar. |
| MaxConnections | 2147483647 | Detta alternativ stöds inte. Det användes för att ange maximal kölängd för lyssning. |
| IPOptions | 1 | Anger IP-alternativet som måste infogas i utgående datagram. |
| HeaderIncluded | 2 | Headern inkluderas i utgående datagram. |
| TypeOfService | 3 | Ändra IP-headerns servicetypfält. |
| IpTimeToLive | 4 | IP:s Time To Live. |
| MulticastInterface | 9 | Ställ in gränssnittet för utgående multicast-paket. |
| MulticastTimeToLive | 10 | IP multicast Time To Live. |
| MulticastLoopback | 11 | IP Multicast loopback. |
| AddMembership | 12 | Lägg till ett IP-gruppmedlemskap. |
| DropMembership | 13 | Ta bort ett IP-gruppmedlemskap. |
| DontFragment | 14 | Fragmentera inte IP-datagram. |
| AddSourceMembership | 15 | Gå med i IP-gruppen/källan. |
| DropSourceMembership | 16 | Avsluta IP-gruppen/källan. |
| BlockSource | 17 | Blockera IP-gruppen/källan. |
| UnblockSource | 18 | Avblockera IP-gruppen/källan. |
| PacketInformation | 19 | Ta emot paketinformation för IPv4. |
| HopLimit | 21 | Levererar ett heltal som innehåller paketets HOP-antal. |
| IPProtectionLevel | 23 | Aktiverar begränsning av en IPv6-socket till det angivna området. |
| IPv6Only | 27 | Socketen är begränsad till att endast skicka och ta emot IPv6-paket. |
| NoDelay | 1 | Inaktiverar Nagle-algoritmen för att slå samman sändningspaket. |
| BsdUrgent | 2 | Använd den brådskande datan enligt RFC-1222. |
| Expedited | 2 | Använd den expedierade datan enligt RFC-1222. |
| NoChecksum | 1 | Skicka UDP-datagram med en kontrollsumma satt till noll. |
| ChecksumCoverage | 20 | Ställ in eller hämta UDP-kontrollsummatäckning. |
| UpdateAcceptContext | 28683 | Uppdaterar en klientsocket med samma egenskaper som en lyssnande socket. |
| UpdateConnectContext | 28688 | Uppdaterar en klientsocket med samma egenskaper som en lyssnande socket. |

## Se även

* Namnrymd [System::Net::Sockets](../)
* Bibliotek [Aspose.Slides](../../)