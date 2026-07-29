---
title: SocketFlags
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller konstanta värden för socket-meddelanden.
type: docs
weight: 222
url: /sv/system.net.sockets/socketflags/
---
## SocketFlags enum

Provides constant values for the socket messages.

```cpp
enum class SocketFlags
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Det finns inga flaggor som används för detta anrop. |
| OutOfBand | 1 | Out-of-band-data bearbetas. |
| Peek | 2 | Titta på ett inkommande meddelande. |
| DontRoute | 4 | Skicka ett meddelande utan att använda routningstabeller. |
| Truncated | 256 | Ett meddelande är för stort för att få plats i den angivna bufferten. Det har klippts av. |
| ControlDataTruncated | 512 | Kontrolldata är större än 64 KB och får inte plats i den interna bufferten. Den har klippts av. |
| Broadcast | 1024 | Ett broadcast-paket. |
| Multicast | 2048 | Ett multicast-paket. |
| Partial | 32768 | Ett meddelande som skickats eller mottagits delvis. |

## Se även

* Namnrymd [System::Net::Sockets](../)
* Bibliotek [Aspose.Slides](../../)