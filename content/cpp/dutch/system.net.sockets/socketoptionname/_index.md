---
title: SocketOptionName
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert socketoptienamen voor de Socket-klasse.
type: docs
weight: 248
url: /nl/system.net.sockets/socketoptionname/
---
## SocketOptionName enum

Definieert socket-optienaam voor de [Socket](../socket/)-klasse.

```cpp
enum class SocketOptionName
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Debug | 1 | Registreer debugginginformatie. |
| AcceptConnection | 2 | Geeft aan of een socket luistert naar een inkomende verbinding. |
| ReuseAddress | 4 | Geeft aan of een socket kan worden gebonden aan een adres dat al in gebruik is. |
| KeepAlive | 8 | Schakelt de 'Keep-Alive'-pakketten in voor een socketverbinding. |
| DontRoute | 16 | Geeft aan of een pakket rechtstreeks naar de interface-adressen wordt gestuurd. |
| Broadcast | 32 | Geeft aan of een socket broadcast-berichten kan verzenden. |
| UseLoopback | 64 | Omzeil hardware wanneer mogelijk. |
| Linger | 128 | Het systeem blokkeert het proces bij de sluitpoging totdat het de gegevens kan verzenden. |
| OutOfBandInline | 256 | Ontvangt out-of-band-gegevens in de normale datastroom. |
| DontLinger | n/a | Geeft aan of een socket wordt gesloten zonder lingeren. |
| ExclusiveAddressUse | n/a | Een socket zal het gebonden adres exclusief gebruiken. |
| SendBuffer | 4097 | Specificeert de grootte van de verzendbuffer. |
| ReceiveBuffer | 4098 | Specificeert de grootte van de ontvangstbuffer. |
| SendLowWater | 4099 | Specificeert de minimale hoeveelheid gegevens voor de verzendbewerkingen. |
| ReceiveLowWater | 4100 | Specificeert de minimale hoeveelheid gegevens voor de ontvangstbewerkingen. |
| SendTimeout | 4101 | Specificeert de time-out voor de synchrone verzendbewerkingen. |
| ReceiveTimeout | 4102 | Specificeert de time-out voor de synchrone ontvangstbewerkingen. |
| Error | 4103 | Geeft de foutstatus terug en maakt deze leeg. |
| Type | 4104 | Geeft een sockettype terug. |
| ReuseUnicastPort | 12295 | Geeft aan of het systeem de toewijzing van de tijdelijke poort voor uitgaande verbindingen moet uitstellen. |
| MaxConnections | 2147483647 | Deze optie wordt niet ondersteund. Hij werd gebruikt om de maximale wachtrijlengte voor luisteren op te geven. |
| IPOptions | 1 | Specificeert de IP-optie die moet worden ingevoegd in uitgaande datagrammen. |
| HeaderIncluded | 2 | De header wordt toegevoegd aan uitgaande datagrammen. |
| TypeOfService | 3 | Verandert het type van het service-veld in de IP-header. |
| IpTimeToLive | 4 | De IP-time-to-live. |
| MulticastInterface | 9 | Stel de interface in voor uitgaande multicast-pakketten. |
| MulticastTimeToLive | 10 | De IP-multicast-time-to-live. |
| MulticastLoopback | 11 | De IP-multicast-loopback. |
| AddMembership | 12 | Voeg een IP-groepslidmaatschap toe. |
| DropMembership | 13 | Verwijder een IP-groepslidmaatschap. |
| DontFragment | 14 | Fragment niet de IP-datagrammen. |
| AddSourceMembership | 15 | Word lid van de IP-groep/bron. |
| DropSourceMembership | 16 | Verwijder de IP-groep/bron. |
| BlockSource | 17 | Blokkeer de IP-groep/bron. |
| UnblockSource | 18 | Deblokkeer de IP-groep/bron. |
| PacketInformation | 19 | Ontvang pakketinformatie voor IPv4. |
| HopLimit | 21 | Levert een geheel getal met de HOP-telling van het pakket. |
| IPProtectionLevel | 23 | Schakelt de beperking van een IPv6-socket tot het opgegeven bereik in. |
| IPv6Only | 27 | De socket mag alleen IPv6-pakketten verzenden en ontvangen. |
| NoDelay | 1 | Schakelt het Nagle-algoritme uit voor het samenvoegen van verzendpakketten. |
| BsdUrgent | 2 | Gebruik de dringende gegevens zoals gedefinieerd in RFC-1222. |
| Expedited | 2 | Gebruik de versnelde gegevens zoals gedefinieerd in RFC-1222. |
| NoChecksum | 1 | Verzend de UDP-datagrammen met een checksum ingesteld op nul. |
| ChecksumCoverage | 20 | Stel de UDP-checksumdekking in of haal deze op. |
| UpdateAcceptContext | 28683 | Werk een client-socket bij met dezelfde eigenschappen als een luister-socket. |
| UpdateConnectContext | 28688 | Werk een client-socket bij met dezelfde eigenschappen als een luister-socket. |

## Zie ook

* Naamruimte [System::Net::Sockets](../)
* Bibliotheek [Aspose.Slides](../../)