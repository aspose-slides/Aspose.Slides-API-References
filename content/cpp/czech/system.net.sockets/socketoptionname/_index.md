---
title: SocketOptionName
second_title: Aspose.Slides pro C++ referenční dokumentace API
description: Definuje názvy možností socketu pro třídu Socket.
type: docs
weight: 248
url: /cs/system.net.sockets/socketoptionname/
---
## SocketOptionName enum

Defines socket option names for the [Socket](../socket/) class.

```cpp
enum class SocketOptionName
```

### Values

| Název | Hodnota | Popis |
| --- | --- | --- |
| Debug | 1 | Zaznamenává informace o ladění. |
| AcceptConnection | 2 | Určuje, zda socket poslouchá na příchozí připojení. |
| ReuseAddress | 4 | Určuje, zda může být socket navázán na adresu, která je již používána. |
| KeepAlive | 8 | Povoluje pakety 'Keep-Alive' pro socketové připojení. |
| DontRoute | 16 | Určuje, zda je paket odeslán přímo na adresy rozhraní. |
| Broadcast | 32 | Určuje, zda může socket odesílat broadcast zprávy. |
| UseLoopback | 64 | Oobejde hardware, pokud je to možné. |
| Linger | 128 | Systém zablokuje proces při pokusu o uzavření, dokud nebude možné data přenést. |
| OutOfBandInline | 256 | Přijímá out-of-band data v běžném datovém proudu. |
| DontLinger | n/a | Určuje, zda bude socket uzavřen bez lingeru. |
| ExclusiveAddressUse | n/a | Socket bude výlučně používat svázanou adresu. |
| SendBuffer | 4097 | Určuje velikost odesílacího vyrovnávacího prostoru. |
| ReceiveBuffer | 4098 | Určuje velikost přijímacího vyrovnávacího prostoru. |
| SendLowWater | 4099 | Určuje minimální množství dat pro odesílací operace. |
| ReceiveLowWater | 4100 | Určuje minimální množství dat pro přijímací operace. |
| SendTimeout | 4101 | Určuje časový limit pro synchronní odesílací operace. |
| ReceiveTimeout | 4102 | Určuje časový limit pro synchronní přijímací operace. |
| Error | 4103 | Vrací stav chyby a vymaže jej. |
| Type | 4104 | Vrací typ socketu. |
| ReuseUnicastPort | 12295 | Určuje, zda by systém měl odložit přidělení efemérního portu pro odchozí spojení. |
| MaxConnections | 2147483647 | Tato volba není podporována. Používala se k určení maximální délky fronty pro naslouchání. |
| IPOptions | 1 | Určuje IP volbu, která musí být vložena do odchozích datagramů. |
| HeaderIncluded | 2 | Hlavička je zahrnuta do odchozích datagramů. |
| TypeOfService | 3 | Změní typ služby v IP hlavičce. |
| IpTimeToLive | 4 | IP čas životnosti (TTL). |
| MulticastInterface | 9 | Nastaví rozhraní pro odchozí multicast pakety. |
| MulticastTimeToLive | 10 | IP multicast čas životnosti. |
| MulticastLoopback | 11 | IP multicast loopback. |
| AddMembership | 12 | Přidá členství v IP skupině. |
| DropMembership | 13 | Odstraní členství v IP skupině. |
| DontFragment | 14 | Nefragmentuje IP datagramy. |
| AddSourceMembership | 15 | Připojí se k IP skupině/zdroji. |
| DropSourceMembership | 16 | Odstraní IP skupinu/zdroj. |
| BlockSource | 17 | Zablokuje IP skupinu/zdroj. |
| UnblockSource | 18 | Odblokuje IP skupinu/zdroj. |
| PacketInformation | 19 | Přijímá informace o paketu pro IPv4. |
| HopLimit | 21 | Vrací celé číslo obsahující počet HOP paketů. |
| IPProtectionLevel | 23 | Umožňuje omezit IPv6 socket na zadaný rozsah. |
| IPv6Only | 27 | Socket je omezen na odesílání a přijímání pouze IPv6 paketů. |
| NoDelay | 1 | Vypíná Nagleův algoritmus pro slučování odesílaných paketů. |
| BsdUrgent | 2 | Používá urgentní data definovaná v RFC-1222. |
| Expedited | 2 | Používá urychlená data definovaná v RFC-1222. |
| NoChecksum | 1 | Odesílá UDP datagramy s kontrolním součtem nastaveným na nulu. |
| ChecksumCoverage | 20 | Nastaví nebo získá rozsah UDP kontrolního součtu. |
| UpdateAcceptContext | 28683 | Aktualizuje klientský socket se stejnými vlastnostmi jako naslouchající socket. |
| UpdateConnectContext | 28688 | Aktualizuje klientský socket se stejnými vlastnostmi jako naslouchající socket. |

## Viz také

* jmenný prostor [System::Net::Sockets](../)
* Knihovna [Aspose.Slides](../../)