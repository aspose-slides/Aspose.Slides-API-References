---
title: SocketOptionName
second_title: Aspose.Slides dla C++ – odniesienie do API
description: Definiuje nazwy opcji socket dla klasy Socket.
type: docs
weight: 248
url: /pl/system.net.sockets/socketoptionname/
---
## SocketOptionName enum

Definiuje nazwy opcji socket dla klasy [Socket](../socket/).

```cpp
enum class SocketOptionName
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Debug | 1 | Rejestruj informacje debugowania. |
| AcceptConnection | 2 | Określa, czy socket nasłuchuje połączenia przychodzącego. |
| ReuseAddress | 4 | Określa, czy socket może być powiązany z adresem, który jest już używany. |
| KeepAlive | 8 | Włącza pakiety 'Keep-Alive' dla połączenia socket. |
| DontRoute | 16 | Określa, czy pakiet jest wysyłany bezpośrednio do adresów interfejsu. |
| Broadcast | 32 | Określa, czy socket może wysyłać wiadomości broadcast. |
| UseLoopback | 64 | Omija sprzęt, gdy to możliwe. |
| Linger | 128 | System zablokuje proces przy próbie zamknięcia, dopóki nie będzie w stanie przesłać danych. |
| OutOfBandInline | 256 | Odbiera dane out-of-band w normalnym strumieniu danych. |
| DontLinger | n/a | Określa, czy socket zostanie zamknięty bez oczekiwania. |
| ExclusiveAddressUse | n/a | Socket będzie używał powiązanego adresu wyłącznie. |
| SendBuffer | 4097 | Określa rozmiar bufora wysyłania. |
| ReceiveBuffer | 4098 | Określa rozmiar bufora odbioru. |
| SendLowWater | 4099 | Określa minimalną ilość danych dla operacji wysyłania. |
| ReceiveLowWater | 4100 | Określa minimalną ilość danych dla operacji odbioru. |
| SendTimeout | 4101 | Określa limit czasu dla synchronicznych operacji wysyłania. |
| ReceiveTimeout | 4102 | Określa limit czasu dla synchronicznych operacji odbioru. |
| Error | 4103 | Zwraca status błędu i czyści go. |
| Type | 4104 | Zwraca typ socket. |
| ReuseUnicastPort | 12295 | Określa, czy system powinien odroczyć przydział tymczasowego portu dla połączeń wychodzących. |
| MaxConnections | 2147483647 | Ta opcja nie jest obsługiwana. Była używana do określenia maksymalnej długości kolejki nasłuchiwania. |
| IPOptions | 1 | Określa opcję IP, która musi być wstawiona do wychodzących datagramów. |
| HeaderIncluded | 2 | Nagłówek jest dołączany do wychodzących datagramów. |
| TypeOfService | 3 | Zmienia typ pola service w nagłówku IP. |
| IpTimeToLive | 4 | Czas życia IP. |
| MulticastInterface | 9 | Ustawia interfejs dla wychodzących pakietów multicast. |
| MulticastTimeToLive | 10 | Czas życia multicast IP. |
| MulticastLoopback | 11 | Loopback multicast IP. |
| AddMembership | 12 | Dodaje przynależność do grupy IP. |
| DropMembership | 13 | Usuwa przynależność do grupy IP. |
| DontFragment | 14 | Nie fragmentuje datagramów IP. |
| AddSourceMembership | 15 | Dołącza do grupy/źródła IP. |
| DropSourceMembership | 16 | Usuwa grupę/źródło IP. |
| BlockSource | 17 | Blokuje grupę/źródło IP. |
| UnblockSource | 18 | Odblokowuje grupę/źródło IP. |
| PacketInformation | 19 | Odbiera informacje o pakiecie dla IPv4. |
| HopLimit | 21 | Zwraca liczbę całkowitą zawierającą liczbę HOP pakietu. |
| IPProtectionLevel | 23 | Włącza ograniczenie socket IPv6 do określonego zakresu. |
| IPv6Only | 27 | Socket jest ograniczony do wysyłania i odbierania wyłącznie pakietów IPv6. |
| NoDelay | 1 | Wyłącza algorytm Nagle'a w celu łączenia pakietów wysyłania. |
| BsdUrgent | 2 | Używa danych pilnych zgodnie z RFC-1222. |
| Expedited | 2 | Używa danych przyspieszonych zgodnie z RFC-1222. |
| NoChecksum | 1 | Wysyła datagramy UDP z sumą kontrolną ustawioną na zero. |
| ChecksumCoverage | 20 | Ustawia lub pobiera zasięg sumy kontrolnej UDP. |
| UpdateAcceptContext | 28683 | Aktualizuje socket klienta o te same właściwości co socket nasłuchujący. |
| UpdateConnectContext | 28688 | Aktualizuje socket klienta o te same właściwości co socket nasłuchujący. |

## Zobacz także

* Przestrzeń nazw [System::Net::Sockets](../)
* Biblioteka [Aspose.Slides](../../)