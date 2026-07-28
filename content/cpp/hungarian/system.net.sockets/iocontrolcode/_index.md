---
title: IOControlCode
second_title: Aspose.Slides C++ API-referencia
description: Felsorolja az IO vezérlőkódokat.
type: docs
weight: 157
url: /hu/system.net.sockets/iocontrolcode/
---
## IOControlCode enum

Enumerálja a [IO](../../system.io/) vezérlőkódokat.

```cpp
enum class IOControlKey : int64_t
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| AsyncIO | -2147195267 | Engedélyezi vagy letiltja a socket aszinkron I/O módját. |
| NonBlockingIO | -2147195266 | A socketet nem blokkolóként jelöli. |
| DataToRead | 1074030207 | Visszaadja a beolvasásra rendelkezésre álló bájtok számát. |
| OobDataRead | 1074033415 | Visszaad információt a beérkezésre váró out-of-band adatról. |
| AssociateHandle | -2013265919 | Társítja ezt a socketet a megadott kezelővel egy kiegészítő interfészben. |
| EnableCircularQueuing | 671088642 | A legrégebbi sorba állított datagramot kicseréli egy bejövővel, ha a bejövő üzenet-sorok teljesek. |
| Flush | 671088644 | Eldobja a jelenlegi tartalmat a sockethez tartozó küldő sorban. |
| GetBroadcastAddress | 1207959557 | Visszaad egy SOCKADDR struktúrát, amely tartalmazza a jelenlegi socket címcsaládjának broadcast címét. |
| GetExtensionFunctionPointer | -939524090 | Lekéri a megadott kiterjesztési függvényre mutató pointert, amelyet a hozzárendelt szolgáltatójáték támogat. |
| GetQos | -939524089 | Lekéri a sockethez társított QOS struktúrát. |
| GetGroupQos | -939524088 | Visszaadja a socket csoport QOS attribútumait. |
| MultipointLoopback | -2013265911 | Szabályozza, hogy egy helyi számítógépen (nem feltétlenül ugyanazon socketen) egy alkalmazás által egy multicast munkamenetben küldött adatot a loopback interfészen a multicast célcsoporthoz csatlakozott socket megkapja-e. |
| MulticastScope | -2013265910 | Szabályozza, hogy egy multicast csomagot hányszor továbbíthat egy router, amelyet TTL-nek vagy hop számlálónak is neveznek. |
| SetQos | -2013265909 | Beállítja a socket QOS attribútumait. |
| SetGroupQos | -2013265908 | Beállítja a socket csoport QOS attribútumait. |
| TranslateHandle | -939524083 | Visszaad egy kezelőt a sockethez, amely érvényes egy kiegészítő interfész kontextusában. |
| RoutingInterfaceQuery | -939524076 | Visszaadja az interfész címeket, amelyeket a megadott távoli címhez való csatlakozáshoz lehet használni. |
| RoutingInterfaceChange | -2013265899 | Engedélyezi az értesítés fogadását, amikor a távoli végpont eléréséhez használt helyi interfész változik. |
| AddressListQuery | 1207959574 | Visszaadja a helyi interfészek listáját, amelyekhez a socket kötődhet. |
| AddressListChange | 671088663 | Engedélyezi az értesítés fogadását, amikor a socket protokollcsaládjának helyi interfészeinek listája változik. |
| QueryTargetPnpHandle | 1207959576 | Lekéri az alapszolgáltató SOCKET kezelőjét. |
| NamespaceChange | -2013265895 | Szabályozza, hogy a socket értesítést kap-e, amikor egy névtér lekérdezés érvénytelen lesz. |
| AddressListSort | -939524071 | Rendezi az IPv6 és IPv4 célcímek listáját, hogy meghatározza a legjobb elérhető címet a kapcsolat létrehozásához. |
| ReceiveAll | -1744830463 | Engedélyezi az összes IPv4 csomag fogadását a hálózaton. |
| ReceiveAllMulticast | -1744830462 | Engedélyezi az összes multicast IPv4 csomag fogadását a hálózaton. |
| ReceiveAllIgmpMulticast | -1744830461 | Engedélyezi az összes IGMP csomag fogadását a hálózaton. |
| KeepAliveValues | -1744830460 | Szabályozza a TCP keep-alive csomagok küldését és azok küldési intervallumát. |
| AbsorbRouterAlert | -1744830459 | Ez az érték megegyezik a Winsock 2 'SIO_ABSORB_RTRALERT' állandóval. |
| UnicastInterface | -1744830458 | Beállítja a kimenő unicast csomagokhoz használt interfészt. |
| LimitBroadcasts | -1744830457 | Ez az érték megegyezik a Winsock 2 'SIO_LIMIT_BROADCASTS' állandóval. |
| BindToInterface | -1744830456 | A socketet egy megadott interfész indexhez köti. |
| MulticastInterface | -1744830455 | Beállítja a kimenő multicast csomagokhoz használt interfészt. |
| AddMulticastGroupOnInterface | -1744830454 | Multicast csoporthoz csatlakozik egy index által azonosított interfész használatával. |
| DeleteMulticastGroupFromInterface | -1744830453 | Eltávolítja a socketet egy multicast csoportból. |

## Lásd még

* Névtér [System::Net::Sockets](../)
* Könyvtár [Aspose.Slides](../../)