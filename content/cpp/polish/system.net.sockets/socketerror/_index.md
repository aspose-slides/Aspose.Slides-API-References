---
title: SocketError
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Wylicza typy błędów socket.
type: docs
weight: 209
url: /pl/system.net.sockets/socketerror/
---
## SocketError enum

Wylicza typy błędów socket.

```cpp
enum class SocketError
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Success | 0 | Operacja socket zakończyła się pomyślnie. |
| SocketError | -1 | Wystąpił nieokreślony błąd socket. |
| Interrupted | 10004 | Blokujące wywołanie socket zostało anulowane. |
| AccessDenied | 10013 | Dostęp do socketu został odmówiony. |
| Fault | 10014 | Wykryto nieprawidłowy adres wskaźnika. |
| InvalidArgument | 10022 | Podano nieprawidłowy argument. |
| TooManyOpenSockets | 10024 | W podkładzie socketów jest zbyt wiele otwartych socketów. |
| WouldBlock | 10035 | Operacja nie może zostać natychmiast zakończona na nieblokującym socket. |
| InProgress | 10036 | Blokująca operacja jest w trakcie. |
| AlreadyInProgress | 10037 | Nieblokujący socket ma już uruchomioną operację. |
| NotSocket | 10038 | Próba wywołania operacji socket na nie-socket. |
| DestinationAddressRequired | 10039 | Wymagany adres został pominięty w operacji socket. |
| MessageSize | 10040 | Datagram jest zbyt długi. |
| ProtocolType | 10041 | Ten socket nie obsługuje podanego typu protokołu. |
| ProtocolOption | 10042 | Użyto nieznanej, nieprawidłowej lub nieobsługiwanej opcji lub poziomu. |
| ProtocolNotSupported | 10043 | Protokół nie jest zaimplementowany lub nie jest skonfigurowany. |
| SocketNotSupported | 10044 | Rodzina adresów nie obsługuje określonego socketu. |
| OperationNotSupported | 10045 | Rodzina protokołów nie obsługuje rodziny adresów. |
| ProtocolFamilyNotSupported | 10046 | Rodzina protokołów nie jest zaimplementowana lub nie jest skonfigurowana. |
| AddressFamilyNotSupported | 10047 | Podana rodzina adresów nie jest obsługiwana. |
| AddressAlreadyInUse | 10048 | Adres może być użyty tylko raz. |
| AddressNotAvailable | 10049 | Wybrany adres IP nie jest prawidłowy w tym kontekście. |
| NetworkDown | 10050 | Sieć jest niedostępna. |
| NetworkUnreachable | 10051 | Brak trasy do zdalnego hosta. |
| NetworkReset | 10052 | Aplikacja próbowała ustawić 'Keep-Alive' na połączeniu, które już przekroczyło limit czasu. |
| ConnectionAborted | 10053 | Połączenie zostało przerwane. |
| ConnectionReset | 10054 | Połączenie zostało zresetowane przez zdalny węzeł. |
| NoBufferSpaceAvailable | 10055 | Brak wolnego miejsca w buforze dla operacji socket. |
| IsConnected | 10056 | Socket jest już połączony. |
| NotConnected | 10057 | Aplikacja próbowała wysłać lub odebrać dane, a socket nie jest połączony. |
| Shutdown | 10058 | Żądanie wysłania lub odebrania danych jest zabronione, ponieważ socket został już zamknięty. |
| TimedOut | 10060 | Próba połączenia przekroczyła limit czasu lub podłączony host nie odpowiedział. |
| ConnectionRefused | 10061 | Zdalny host aktywnie odrzuca połączenie. |
| HostDown | 10064 | Operacja nie powiodła się, ponieważ zdalny host jest niedostępny. |
| HostUnreachable | 10065 | Brak trasy sieciowej do określonego hosta. |
| ProcessLimit | 10067 | Zbyt wiele procesów korzysta z podkładu socketów. |
| SystemNotReady | 10091 | Podsystem sieciowy jest niedostępny. |
| VersionNotSupported | 10092 | Wersja podkładu socketów jest poza zakresem. |
| NotInitialized | 10093 | Podkład socketów nie jest zainicjowany. |
| Disconnecting | 10101 | Trwa łagodne zamknięcie. |
| TypeNotFound | 10109 | Określona klasa nie została znaleziona. |
| HostNotFound | 11001 | Określony host jest nieznany. |
| TryAgain | 11002 | Nie można rozwiązać nazwy hosta. |
| NoRecovery | 11003 | Błąd jest nieodwracalny lub żądanej bazy danych nie można znaleźć. |
| NoData | 11004 | Żądana nazwa lub adres IP nie został znaleziony w serwerze nazw. |

## Zobacz także

* Przestrzeń nazw [System::Net::Sockets](../)
* Biblioteka [Aspose.Slides](../../)