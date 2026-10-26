---
title: IOControlCode
second_title: Dokumentacja API Aspose.Slides dla C++
description: Wylicza kody sterujące I/O.
type: docs
weight: 157
url: /pl/system.net.sockets/iocontrolcode/
---
## IOControlCode enum

Wylicza kody sterujące [IO](../../system.io/).

```cpp
enum class IOControlCode : int64_t
```

### Wartości

| Name | Value | Description |
| --- | --- | --- |
| AsyncIO | -2147195267 | Włącza lub wyłącza asynchroniczny tryb I/O gniazda. |
| NonBlockingIO | -2147195266 | Oznacza gniazdo jako nieblokujące. |
| DataToRead | 1074030207 | Zwraca liczbę bajtów dostępnych do odczytu. |
| OobDataRead | 1074033415 | Zwraca informacje o danych poza pasmem oczekujących na odebranie. |
| AssociateHandle | -2013265919 | Łączy to gniazdo z określonym uchwytem interfejsu towarzyszącego. |
| EnableCircularQueuing | 671088642 | Zastępuje najstarszy kolejkowany datagram nowym, gdy kolejki przychodzących wiadomości są pełne. |
| Flush | 671088644 | Usuwa bieżącą zawartość kolejki wysyłania związaną z tym gniazdem. |
| GetBroadcastAddress | 1207959557 | Zwraca strukturę SOCKADDR zawierającą adres rozgłoszeniowy dla rodziny adresów bieżącego gniazda. |
| GetExtensionFunctionPointer | -939524090 | Pobiera wskaźnik do określonej funkcji rozszerzenia obsługiwanej przez powiązanego dostawcę usług. |
| GetQos | -939524089 | Pobiera strukturę QOS powiązaną z gniazdem. |
| GetGroupQos | -939524088 | Zwraca atrybuty QOS dla grupy gniazd. |
| MultipointLoopback | -2013265911 | Steruje, czy dane wysłane przez aplikację na komputerze lokalnym (niekoniecznie tym samym gniazdem) w sesji multicast będą odbierane przez gniazdo dołączone do grupy docelowej multicast na interfejsie loopback. |
| MulticastScope | -2013265910 | Steruje liczbą przeskoków, jakie pakiet multicast może wykonać przez router, znane także jako TTL lub liczba przeskoków. |
| SetQos | -2013265909 | Ustawia atrybuty QOS dla gniazda. |
| SetGroupQos | -2013265908 | Ustawia atrybuty QOS dla grupy gniazd. |
| TranslateHandle | -939524083 | Zwraca uchwyt do gniazda ważny w kontekście interfejsu towarzyszącego. |
| RoutingInterfaceQuery | -939524076 | Zwraca adresy interfejsów, które mogą być użyte do połączenia ze wskazanym zdalnym adresem. |
| RoutingInterfaceChange | -2013265899 | Włącza odbieranie powiadomienia, gdy zmieni się lokalny interfejs używany do dostępu do zdalnego punktu końcowego. |
| AddressListQuery | 1207959574 | Zwraca listę lokalnych interfejsów, do których gniazdo może się przywiązać. |
| AddressListChange | 671088663 | Włącza odbieranie powiadomienia, gdy zmieni się lista lokalnych interfejsów dla rodziny protokołów gniazda. |
| QueryTargetPnpHandle | 1207959576 | Pobiera podstawowy uchwyt SOCKET dostawcy. |
| NamespaceChange | -2013265895 | Steruje, czy gniazdo otrzymuje powiadomienie, gdy zapytanie przestrzeni nazw staje się nieprawidłowe. |
| AddressListSort | -939524071 | Sortuje listę docelowych adresów IPv6 i IPv4, aby określić najlepszy dostępny adres do nawiązania połączenia. |
| ReceiveAll | -1744830463 | Włącza odbieranie wszystkich pakietów IPv4 w sieci. |
| ReceiveAllMulticast | -1744830462 | Włącza odbieranie wszystkich pakietów multicast IPv4 w sieci. |
| ReceiveAllIgmpMulticast | -1744830461 | Włącza odbieranie wszystkich pakietów IGMP w sieci. |
| KeepAliveValues | -1744830460 | Steruje wysyłaniem pakietów TCP keep-alive oraz interwałem ich wysyłania. |
| AbsorbRouterAlert | -1744830459 | Ta wartość jest równa stałej Winsock 2 'SIO_ABSORB_RTRALERT'. |
| UnicastInterface | -1744830458 | Ustawia interfejs używany do wychodzących pakietów unicast. |
| LimitBroadcasts | -1744830457 | Ta wartość jest równa stałej Winsock 2 'SIO_LIMIT_BROADCASTS'. |
| BindToInterface | -1744830456 | Łączy gniazdo z określonym indeksem interfejsu. |
| MulticastInterface | -1744830455 | Ustawia interfejs używany do wychodzących pakietów multicast. |
| AddMulticastGroupOnInterface | -1744830454 | Dołącza do grupy multicast przy użyciu interfejsu zidentyfikowanego przez jego indeks. |
| DeleteMulticastGroupFromInterface | -1744830453 | Usuwa gniazdo z grupy multicast. |

## Zobacz także

* Przestrzeń nazw [System::Net::Sockets](../)
* Biblioteka [Aspose.Slides](../../)