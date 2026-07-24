---
title: SocketOptionName
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert Socket-Optionnamen für die Socket-Klasse.
type: docs
weight: 248
url: /de/system.net.sockets/socketoptionname/
---
## SocketOptionName enum


Definiert Socket-Optionnamen für die [Socket](../socket/) Klasse.

```cpp
enum class SocketOptionName
```

### Werte

| Name | Value | Description |
| --- | --- | --- |
| Debug | 1 | Debug-Informationen aufzeichnen. |
| AcceptConnection | 2 | Gibt an, ob ein Socket auf eingehende Verbindungen wartet. |
| ReuseAddress | 4 | Gibt an, ob ein Socket an eine bereits genutzte Adresse gebunden werden kann. |
| KeepAlive | 8 | Aktiviert die ‘Keep-Alive’-Pakete für eine Socket-Verbindung. |
| DontRoute | 16 | Gibt an, ob ein Paket direkt an die Interface-Adressen gesendet wird. |
| Broadcast | 32 | Gibt an, ob ein Socket Broadcast-Nachrichten senden kann. |
| UseLoopback | 64 | Umgeht die Hardware, wenn möglich. |
| Linger | 128 | Das System blockiert den Prozess beim Schließen, bis die Daten übertragen werden können. |
| OutOfBandInline | 256 | Empfängt Out-of-Band-Daten im normalen Datenstrom. |
| DontLinger | n/a | Gibt an, ob ein Socket ohne Linger geschlossen wird. |
| ExclusiveAddressUse | n/a | Ein Socket verwendet die gebundene Adresse ausschließlich. |
| SendBuffer | 4097 | Gibt die Größe des Sendepuffers an. |
| ReceiveBuffer | 4098 | Gibt die Größe des Empfangspuffers an. |
| SendLowWater | 4099 | Gibt die minimale Datenmenge für Sendvorgänge an. |
| ReceiveLowWater | 4100 | Gibt die minimale Datenmenge für Empfangsvorgänge an. |
| SendTimeout | 4101 | Gibt den Timeout für synchrone Sendvorgänge an. |
| ReceiveTimeout | 4102 | Gibt den Timeout für synchrone Empfangsvorgänge an. |
| Error | 4103 | Gibt den Fehlstatus zurück und löscht ihn. |
| Type | 4104 | Gibt einen Socket-Typ zurück. |
| ReuseUnicastPort | 12295 | Gibt an, ob das System die Zuweisung temporärer Ports für ausgehende Verbindungen aufschieben soll. |
| MaxConnections | 2147483647 | Diese Option wird nicht unterstützt. Sie wurde verwendet, um die maximale Warteschlangenlänge für das Lauschen anzugeben. |
| IPOptions | 1 | Gibt die IP-Option an, die in ausgehende Datagramme eingefügt werden muss. |
| HeaderIncluded | 2 | Der Header wird in ausgehende Datagramme eingeschlossen. |
| TypeOfService | 3 | Ändert das Dienstfeld im IP-Header. |
| IpTimeToLive | 4 | Die IP-Time-to-Live. |
| MulticastInterface | 9 | Legt das Interface für ausgehende Multicast-Pakete fest. |
| MulticastTimeToLive | 10 | Die IP-Multicast-Time-to-Live. |
| MulticastLoopback | 11 | Der IP-Multicast-Loopback. |
| AddMembership | 12 | Fügt eine IP-Gruppenmitgliedschaft hinzu. |
| DropMembership | 13 | Entfernt eine IP-Gruppenmitgliedschaft. |
| DontFragment | 14 | Fragmentiert die IP-Datagramme nicht. |
| AddSourceMembership | 15 | Tritt der IP-Gruppe/Quelle bei. |
| DropSourceMembership | 16 | Verlässt die IP-Gruppe/Quelle. |
| BlockSource | 17 | Blockiert die IP-Gruppe/Quelle. |
| UnblockSource | 18 | Hebt die Blockierung der IP-Gruppe/Quelle auf. |
| PacketInformation | 19 | Empfängt Paketinformationen für IPv4. |
| HopLimit | 21 | Gibt einen Integer zurück, der die HOP-Anzahl des Pakets enthält. |
| IPProtectionLevel | 23 | Ermöglicht die Einschränkung eines IPv6-Sockets auf den angegebenen Geltungsbereich. |
| IPv6Only | 27 | Der Socket ist darauf beschränkt, ausschließlich IPv6-Pakete zu senden und zu empfangen. |
| NoDelay | 1 | Deaktiviert den Nagle-Algorithmus zur Zusammenfassung von Sendepaketen. |
| BsdUrgent | 2 | Verwendet die dringenden Daten gemäß RFC-1222. |
| Expedited | 2 | Verwendet die beschleunigten Daten gemäß RFC-1222. |
| NoChecksum | 1 | Sendet die UDP-Datagramme mit einer Prüfsumme von Null. |
| ChecksumCoverage | 20 | Setzt oder liest die UDP-Prüfsummenabdeckung. |
| UpdateAcceptContext | 28683 | Aktualisiert einen Client-Socket mit den gleichen Eigenschaften wie ein lauscher Socket. |
| UpdateConnectContext | 28688 | Aktualisiert einen Client-Socket mit den gleichen Eigenschaften wie ein lauscher Socket. |

## Siehe auch

* Namensraum [System::Net::Sockets](../)
* Bibliothek [Aspose.Slides](../../)