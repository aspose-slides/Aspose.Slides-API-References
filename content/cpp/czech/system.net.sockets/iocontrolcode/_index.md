---
title: IOControlCode
second_title: Aspose.Slides pro C++ – reference API
description: Vyjmenovává kontrolní kódy IO.
type: docs
weight: 157
url: /cs/system.net.sockets/iocontrolcode/
---
## IOControlCode enum

Vypisuje kontrolní kódy [IO](../../system.io/).

```cpp
enum class IOControlCode : int64_t
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| AsyncIO | -2147195267 | Povolí nebo zakáže asynchronní režim I/O soketu. |
| NonBlockingIO | -2147195266 | Označí soket jako neblokující. |
| DataToRead | 1074030207 | Vrátí počet bajtů dostupných ke čtení. |
| OobDataRead | 1074033415 | Vrátí informace o out-of-band datech čekajících na přijetí. |
| AssociateHandle | -2013265919 | Přiřadí tento soket k určenému handle společního rozhraní. |
| EnableCircularQueuing | 671088642 | Nahradí nejstarší zařazený datagram novým, pokud jsou fronty příchozích zpráv plné. |
| Flush | 671088644 | Zahodí aktuální obsah odesílací fronty spojené s tímto soketem. |
| GetBroadcastAddress | 1207959557 | Vrátí strukturu SOCKADDR, která obsahuje broadcastovou adresu pro rodinu adres aktuálního soketu. |
| GetExtensionFunctionPointer | -939524090 | Získá ukazatel na uvedenou rozšiřující funkci podporovanou přidruženým poskytovatelem služeb. |
| GetQos | -939524089 | Získá strukturu QOS spojenou se soketem. |
| GetGroupQos | -939524088 | Vrátí atributy QOS pro skupinu soketů. |
| MultipointLoopback | -2013265911 | Určuje, zda data odeslaná aplikací na lokálním počítači (ne nutně stejným soketem) v multicast relaci budou přijata soketem připojeným ke skupině cílových multicastů na rozhraní loopback. |
| MulticastScope | -2013265910 | Určuje počet přenosů multicast paketu směrovačem, známý také jako TTL nebo počet skoků. |
| SetQos | -2013265909 | Nastaví atributy QOS pro soket. |
| SetGroupQos | -2013265908 | Nastaví atributy QOS pro skupinu soketů. |
| TranslateHandle | -939524083 | Vrátí handle pro soket platný v kontextu společního rozhraní. |
| RoutingInterfaceQuery | -939524076 | Vrátí adresy rozhraní, které lze použít k připojení k určené vzdálené adrese. |
| RoutingInterfaceChange | -2013265899 | Povolí přijímání oznámení, když se změní lokální rozhraní použité pro přístup ke vzdálenému koncovému bodu. |
| AddressListQuery | 1207959574 | Vrátí seznam lokálních rozhraní, ke kterým se může soket připojit. |
| AddressListChange | 671088663 | Povolí přijímání oznámení, když se změní seznam lokálních rozhraní pro protokolovou rodinu soketu. |
| QueryTargetPnpHandle | 1207959576 | Získá podkladový SOCKET handle poskytovatele. |
| NamespaceChange | -2013265895 | Určuje, zda soket přijímá oznámení, když se dotaz na jmenný prostor stane neplatným. |
| AddressListSort | -939524071 | Setřídí seznam cílových adres IPv6 a IPv4 pro určení nejlepší dostupné adresy pro navázání spojení. |
| ReceiveAll | -1744830463 | Povolí přijímání všech IPv4 paketů v síti. |
| ReceiveAllMulticast | -1744830462 | Povolí přijímání všech multicast IPv4 paketů v síti. |
| ReceiveAllIgmpMulticast | -1744830461 | Povolí přijímání všech IGMP paketů v síti. |
| KeepAliveValues | -1744830460 | Určuje odesílání TCP keep-alive paketů a interval jejich odesílání. |
| AbsorbRouterAlert | -1744830459 | Tato hodnota je stejná jako konstanta Winsock 2 'SIO_ABSORB_RTRALERT'. |
| UnicastInterface | -1744830458 | Nastaví rozhraní použité pro odchozí unicast pakety. |
| LimitBroadcasts | -1744830457 | Tato hodnota je stejná jako konstanta Winsock 2 'SIO_LIMIT_BROADCASTS'. |
| BindToInterface | -1744830456 | Připojí soket k určenému indexu rozhraní. |
| MulticastInterface | -1744830455 | Nastaví rozhraní použité pro odchozí multicast pakety. |
| AddMulticastGroupOnInterface | -1744830454 | Připojí se k multicast skupině pomocí rozhraní identifikovaného jeho indexem. |
| DeleteMulticastGroupFromInterface | -1744830453 | Odstraní soket z multicast skupiny. |

## Viz také

* Jmenný prostor [System::Net::Sockets](../)
* Knihovna [Aspose.Slides](../../)