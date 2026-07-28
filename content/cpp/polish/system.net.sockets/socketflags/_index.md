---
title: SocketFlags
second_title: Aspose.Slides dla C++ – referencja API
description: Udostępnia stałe wartości dla komunikatów socket.
type: docs
weight: 222
url: /pl/system.net.sockets/socketflags/
---
## SocketFlags enum

Provides constant values for the socket messages.

```cpp
enum class SocketFlags
```

### Values

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| None | 0 | Nie użyto żadnych flag w tym wywołaniu. |
| OutOfBand | 1 | Dane poza pasmem są przetwarzane. |
| Peek | 2 | Podgląd przychodzącej wiadomości. |
| DontRoute | 4 | Wyślij wiadomość bez użycia tablic routingu. |
| Truncated | 256 | Wiadomość jest za duża, aby zmieścić się w określonym buforze. Została obcięta. |
| ControlDataTruncated | 512 | Dane kontrolne są większe niż 64 KB i nie mieszczą się w wewnętrznym buforze. Zostały obcięte. |
| Broadcast | 1024 | Pakiet rozgłoszeniowy. |
| Multicast | 2048 | Pakiet multicast. |
| Partial | 32768 | Wiadomość wysłana lub odebrana częściowo. |

## Zobacz także

* Przestrzeń nazw [System::Net::Sockets](../)
* Biblioteka [Aspose.Slides](../../)