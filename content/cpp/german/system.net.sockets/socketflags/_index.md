---
title: SocketFlags
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt konstante Werte für die Socket-Nachrichten bereit.
type: docs
weight: 222
url: /de/system.net.sockets/socketflags/
---
## SocketFlags enum

Stellt konstante Werte für die Socket-Nachrichten bereit.

```cpp
enum class SocketFlags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Für diesen Aufruf werden keine Flags verwendet. |
| OutOfBand | 1 | Out-of-Band-Daten werden verarbeitet. |
| Peek | 2 | Vorschau auf eine eingehende Nachricht. |
| DontRoute | 4 | Sende eine Nachricht ohne Routing-Tabellen zu verwenden. |
| Truncated | 256 | Eine Nachricht ist zu groß, um in den angegebenen Puffer zu passen. Sie wurde abgeschnitten. |
| ControlDataTruncated | 512 | Die Steuerelementdaten sind größer als 64 KB und passen nicht in den internen Puffer. Sie wurden abgeschnitten. |
| Broadcast | 1024 | Ein Broadcast-Paket. |
| Multicast | 2048 | Ein Multicast-Paket. |
| Partial | 32768 | Eine Nachricht, die teilweise gesendet oder empfangen wurde. |

## Siehe auch

* Namensraum [System::Net::Sockets](../)
* Bibliothek [Aspose.Slides](../../)