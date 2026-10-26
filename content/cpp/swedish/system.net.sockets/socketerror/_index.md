---
title: SocketError
second_title: Aspose.Slides för C++ API-referens
description: Enumererar socketfeltyperna.
type: docs
weight: 209
url: /sv/system.net.sockets/socketerror/
---
## SocketError enum

Enumerates the socket error types.

```cpp
enum class SocketError
```

### Values

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Success | 0 | En socketoperation slutfördes framgångsrikt. |
| SocketError | -1 | Ett ospecificerat socketfel inträffade. |
| Interrupted | 10004 | Ett blockerande socketanrop avbröts. |
| AccessDenied | 10013 | Tillgång till en socket nekas. |
| Fault | 10014 | En ogiltig pekaradress upptäcktes. |
| InvalidArgument | 10022 | Ett ogiltigt argument har tillhandahållits. |
| TooManyOpenSockets | 10024 | Det finns för många öppna sockets i den underliggande socketleverantören. |
| WouldBlock | 10035 | En operation kan inte slutföras omedelbart på en icke-blockerande socket. |
| InProgress | 10036 | En blockerande operation pågår. |
| AlreadyInProgress | 10037 | En icke-blockerande socket har redan en pågående operation. |
| NotSocket | 10038 | Ett försök att anropa en socketoperation på icke-socket. |
| DestinationAddressRequired | 10039 | En obligatorisk adress har utelämnats från en socketoperation. |
| MessageSize | 10040 | Ett datagram är för långt. |
| ProtocolType | 10041 | En protokolltyp stöds inte av denna socket. |
| ProtocolOption | 10042 | En okänd, ogiltig eller ej stödd alternativ eller nivå har använts. |
| ProtocolNotSupported | 10043 | Ett protokoll är inte implementerat eller inte konfigurerat. |
| SocketNotSupported | 10044 | En adressfamilj stöder inte den angivna socketen. |
| OperationNotSupported | 10045 | En protokollfamilj stöder inte en adressfamilj. |
| ProtocolFamilyNotSupported | 10046 | En protokollfamilj är inte implementerad eller inte konfigurerad. |
| AddressFamilyNotSupported | 10047 | Den angivna adressfamiljen stöds inte. |
| AddressAlreadyInUse | 10048 | En adress kan endast användas en gång. |
| AddressNotAvailable | 10049 | Den valda IP-adressen är inte giltig i detta sammanhang. |
| NetworkDown | 10050 | Nätverket är inte tillgängligt. |
| NetworkUnreachable | 10051 | Ingen rutt till fjärrvärden finns. |
| NetworkReset | 10052 | Ett program försökte sätta 'Keep-Alive' på en anslutning som redan har gått ut. |
| ConnectionAborted | 10053 | En anslutning avbröts. |
| ConnectionReset | 10054 | En anslutning återställs av en fjärrpart. |
| NoBufferSpaceAvailable | 10055 | Ingen ledig buffertutrymme är tillgängligt för en socketoperation. |
| IsConnected | 10056 | En socket är redan ansluten. |
| NotConnected | 10057 | Ett program försökte skicka eller ta emot data, men en socket är inte ansluten. |
| Shutdown | 10058 | En begäran om att skicka eller ta emot data är förbjuden eftersom socketen redan har stängts. |
| TimedOut | 10060 | Ett anslutningsförsök löpte ut, eller en ansluten värd svarade inte. |
| ConnectionRefused | 10061 | En fjärrvärd vägrar aktivt en anslutning. |
| HostDown | 10064 | En operation misslyckades eftersom en fjärrvärd är nere. |
| HostUnreachable | 10065 | Ingen nätverksrutt till den angivna värden finns. |
| ProcessLimit | 10067 | För många processer använder den underliggande socketleverantören. |
| SystemNotReady | 10091 | Ett nätverkssubsystem är otillgängligt. |
| VersionNotSupported | 10092 | En version av den underliggande socketleverantören är utanför intervallet. |
| NotInitialized | 10093 | Den underliggande socketleverantören är inte initierad. |
| Disconnecting | 10101 | En kontrollerad nedstängning pågår. |
| TypeNotFound | 10109 | Den angivna klassen kunde inte hittas. |
| HostNotFound | 11001 | Den angivna värden är okänd. |
| TryAgain | 11002 | Ett namn på en värd kan inte lösas upp. |
| NoRecovery | 11003 | Ett fel är oåterställbart eller den begärda databasen kan inte lokaliseras. |
| NoData | 11004 | Ett begärt namn eller IP-adress finns inte på namntjänsten. |

## Se även

* Namnrymd [System::Net::Sockets](../)
* Bibliotek [Aspose.Slides](../../)