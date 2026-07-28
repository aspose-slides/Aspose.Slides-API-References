---
title: SocketOptionName
second_title: Aspose.Slides C++ API Referenciája
description: A Socket osztály socket opcióneveit definiálja.
type: docs
weight: 248
url: /hu/system.net.sockets/socketoptionname/
---
## SocketOptionName enum


Meghatározza a [Socket](../socket/) osztály socket opcióneveit.

```cpp
enum class SocketOptionName
```

### Értékek

| Name | Value | Description |
| --- | --- | --- |
| Debug | 1 | Rögzíti a hibakeresési információkat. |
| AcceptConnection | 2 | Jelzi, hogy a socket hallgatózik egy bejövő kapcsolatra. |
| ReuseAddress | 4 | Jelzi, hogy a socket kötődik egy már használt címhez. |
| KeepAlive | 8 | Engedélyezi a 'Keep-Alive' csomagokat egy socket kapcsolatnál. |
| DontRoute | 16 | Jelzi, hogy a csomag közvetlenül az interfész címekre kerül elküldésre. |
| Broadcast | 32 | Jelzi, hogy a socket képes broadcast üzeneteket küldeni. |
| UseLoopback | 64 | Hardvert megkerüli, ha lehetséges. |
| Linger | 128 | A rendszer blokkolja a folyamatot a lezárási kísérlet során, amíg az adatátvitel be nem fejeződik. |
| OutOfBandInline | 256 | Kiszolgálja a sávon kívüli adatokat a normál adatfolyamban. |
| DontLinger | n/a | Jelzi, hogy a socket késleltetés nélkül lesz lezárva. |
| ExclusiveAddressUse | n/a | A socket kizárólag a kötött címet fogja használni. |
| SendBuffer | 4097 | Megadja a küldési puffer méretét. |
| ReceiveBuffer | 4098 | Megadja a fogadási puffer méretét. |
| SendLowWater | 4099 | Megadja a küldési műveletekhez szükséges minimális adatméretet. |
| ReceiveLowWater | 4100 | Megadja a fogadási műveletekhez szükséges minimális adatméretet. |
| SendTimeout | 4101 | Megadja a szinkron küldési műveletek időtúllépését. |
| ReceiveTimeout | 4102 | Megadja a szinkron fogadási műveletek időtúllépését. |
| Error | 4103 | Visszaadja a hibastátuszt és törli azt. |
| Type | 4104 | Visszaad egy socket típust. |
| ReuseUnicastPort | 12295 | Jelzi, hogy a rendszer késleltetni kell-e a rövid élettartamú port kiosztását a kimenő kapcsolatokhoz. |
| MaxConnections | 2147483647 | Ez a beállítás nem támogatott. A hallgatás maximális sorhosszát határozta meg. |
| IPOptions | 1 | Megadja az IP opciót, amelyet a kimenő datagramokba kell beilleszteni. |
| HeaderIncluded | 2 | A fejléc be van illesztve a kimenő datagramokba. |
| TypeOfService | 3 | Megváltoztatja az IP fejléc szolgáltatás mezőjének típusát. |
| IpTimeToLive | 4 | Az IP időtartam (TTL). |
| MulticastInterface | 9 | Beállítja az interfészt a kimenő multicast csomagokhoz. |
| MulticastTimeToLive | 10 | Az IP multicast időtartam (TTL). |
| MulticastLoopback | 11 | Az IP Multicast loopback. |
| AddMembership | 12 | IP csoport tagságot ad hozzá. |
| DropMembership | 13 | IP csoport tagságot eltávolít. |
| DontFragment | 14 | Ne darabolja szét az IP datagramokat. |
| AddSourceMembership | 15 | Csatlakozik az IP csoporthoz/forráshoz. |
| DropSourceMembership | 16 | Eltávolítja az IP csoportot/forrást. |
| BlockSource | 17 | Blokkolja az IP csoportot/forrást. |
| UnblockSource | 18 | Feloldja az IP csoport blokkolását/forrást. |
| PacketInformation | 19 | IPv4 csomaginformációk fogadása. |
| HopLimit | 21 | Egy egész számot ad vissza, amely a csomag HOP számát tartalmazza. |
| IPProtectionLevel | 23 | Lehetővé teszi egy IPv6 socket korlátozását a megadott körre. |
| IPv6Only | 27 | A socket kizárólag IPv6 csomagok küldésére és fogadására van korlátozva. |
| NoDelay | 1 | Letiltja a Nagle-algoritmust a küldési csomagok összegyűjtésére. |
| BsdUrgent | 2 | A sürgős adatot használja, ahogyan azt az RFC-1222 definiálja. |
| Expedited | 2 | A gyorsított adatot használja, ahogyan azt az RFC-1222 definiálja. |
| NoChecksum | 1 | Az UDP datagramokat nulla ellenőrzőösszeggel küldi. |
| ChecksumCoverage | 20 | Beállítja vagy lekéri az UDP ellenőrzőösszeg lefedettségét. |
| UpdateAcceptContext | 28683 | Frissíti egy kliens socketet a hallgató socket tulajdonságaival. |
| UpdateConnectContext | 28688 | Frissíti egy kliens socketet a hallgató socket tulajdonságaival. |

## Lásd még

* Névtér [System::Net::Sockets](../)
* Könyvtár [Aspose.Slides](../../)