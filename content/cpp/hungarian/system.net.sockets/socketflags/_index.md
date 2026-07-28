---
title: SocketFlags
second_title: Aspose.Slides a C++ API-referencia
description: Állandó értékeket biztosít a socket üzenetekhez.
type: docs
weight: 222
url: /hu/system.net.sockets/socketflags/
---
## SocketFlags enum


Állandó értékeket biztosít a socket üzenetekhez.

```cpp
enum class SocketFlags
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| None | 0 | Ehhez a híváshoz nincsenek zászlók használva. |
| OutOfBand | 1 | Az out-of-band adat feldolgozásra kerül. |
| Peek | 2 | Megtekint egy bejövő üzenetet. |
| DontRoute | 4 | Üzenet küldése routing táblák használata nélkül. |
| Truncated | 256 | Az üzenet túl nagy a megadott pufferbe való illesztéshez. Le lett csonkolva. |
| ControlDataTruncated | 512 | A vezérlőadat nagyobb mint 64 KB és nem fér el a belső pufferben. Le lett csonkolva. |
| Broadcast | 1024 | Egy broadcast csomag. |
| Multicast | 2048 | Egy multicast csomag. |
| Partial | 32768 | Részben elküldött vagy fogadott üzenet. |

## Lásd még

* Névtér [System::Net::Sockets](../)
* Könyvtár [Aspose.Slides](../../)