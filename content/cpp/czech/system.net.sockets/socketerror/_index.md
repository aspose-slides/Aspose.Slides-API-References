---
title: SocketError
second_title: Aspose.Slides pro C++ API Reference
description: Vypisuje typy chyb socketu.
type: docs
weight: 209
url: /cs/system.net.sockets/socketerror/
---
## SocketError výčet

Enumerates the socket error types.

```cpp
enum class SocketError
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Success | 0 | Operace socketu byla úspěšně dokončena. |
| SocketError | -1 | Došlo k nespecifikované chybě socketu. |
| Interrupted | 10004 | Blokující volání socketu bylo zrušeno. |
| AccessDenied | 10013 | Přístup k socketu byl odmítnut. |
| Fault | 10014 | Byla detekována neplatná adresa ukazatele. |
| InvalidArgument | 10022 | Byl poskytnut neplatný argument. |
| TooManyOpenSockets | 10024 | V základním poskytovateli socketů je příliš mnoho otevřených socketů. |
| WouldBlock | 10035 | Operace nemůže být okamžitě dokončena na neblokujícím socketu. |
| InProgress | 10036 | Blokující operace probíhá. |
| AlreadyInProgress | 10037 | Neblokující socket již má probíhající operaci. |
| NotSocket | 10038 | Pokus o volání operace socketu na objektu, který není socket. |
| DestinationAddressRequired | 10039 | Požadovaná adresa chybí v operaci socketu. |
| MessageSize | 10040 | Datagram je příliš dlouhý. |
| ProtocolType | 10041 | Typ protokolu není tímto socketem podporován. |
| ProtocolOption | 10042 | Je použita neznámá, neplatná nebo nepodporovaná volba či úroveň. |
| ProtocolNotSupported | 10043 | Protokol není implementován nebo není nakonfigurován. |
| SocketNotSupported | 10044 | Rodina adres nepodporuje specifikovaný socket. |
| OperationNotSupported | 10045 | Rodina protokolů nepodporuje rodinu adres. |
| ProtocolFamilyNotSupported | 10046 | Rodina protokolů není implementována nebo není nakonfigurována. |
| AddressFamilyNotSupported | 10047 | Specifikovaná rodina adres není podporována. |
| AddressAlreadyInUse | 10048 | Adresa může být použita pouze jednou. |
| AddressNotAvailable | 10049 | Vybraná IP adresa není v tomto kontextu platná. |
| NetworkDown | 10050 | Síť není k dispozici. |
| NetworkUnreachable | 10051 | Neexistuje trasa k vzdálenému hostiteli. |
| NetworkReset | 10052 | Aplikace se pokusila nastavit 'Keep-Alive' na spojení, které již vypršelo. |
| ConnectionAborted | 10053 | Spojení bylo přerušeno. |
| ConnectionReset | 10054 | Spojení bylo resetováno vzdáleným protějškem. |
| NoBufferSpaceAvailable | 10055 | Pro operaci socketu není k dispozici žádný volný prostor v bufferu. |
| IsConnected | 10056 | Socket je již připojen. |
| NotConnected | 10057 | Aplikace se pokusila odeslat nebo přijmout data, ale socket není připojen. |
| Shutdown | 10058 | Požadavek na odeslání nebo přijetí dat je zakázán, protože socket již byl uzavřen. |
| TimedOut | 10060 | Pokus o spojení vypršel, nebo připojený hostitel neodpověděl. |
| ConnectionRefused | 10061 | Vzdálený hostitel aktivně odmítá spojení. |
| HostDown | 10064 | Operace selhala, protože vzdálený hostitel není dostupný. |
| HostUnreachable | 10065 | Neexistuje síťová trasa k zadanému hostiteli. |
| ProcessLimit | 10067 | Příliš mnoho procesů využívá základní poskytovatel socketů. |
| SystemNotReady | 10091 | Síťový subsystém není dostupný. |
| VersionNotSupported | 10092 | Verze základního poskytovatele socketů je mimo rozsah. |
| NotInitialized | 10093 | Základní poskytovatel socketů není inicializován. |
| Disconnecting | 10101 | Probíhá elegantní ukončení. |
| TypeNotFound | 10109 | Zadaná třída nebyla nalezena. |
| HostNotFound | 11001 | Zadaný hostitel je neznámý. |
| TryAgain | 11002 | Název hostitele nelze rozpoznat. |
| NoRecovery | 11003 | Chyba není obnovitelná nebo požadovaná databáze nelze najít. |
| NoData | 11004 | Požadovaný název nebo IP adresa nebyla nalezena na jmenném serveru. |

## Viz také

* Namespace [System::Net::Sockets](../)
* Library [Aspose.Slides](../../)