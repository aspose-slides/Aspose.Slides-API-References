---
title: SocketError
second_title: Aspose.Slides voor C++ API-referentie
description: Somt de socketfouttypes op.
type: docs
weight: 209
url: /nl/system.net.sockets/socketerror/
---
## SocketError enum

Somt de socketfouttypes op.

```cpp
enum class SocketError
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Success | 0 | Een socketbewerking is succesvol voltooid. |
| SocketError | -1 | Er is een niet-gespecificeerde socketfout opgetreden. |
| Interrupted | 10004 | Een blokkerende socketaanroep is geannuleerd. |
| AccessDenied | 10013 | Toegang tot een socket is geweigerd. |
| Fault | 10014 | Er is een ongeldige pointeradres gedetecteerd. |
| InvalidArgument | 10022 | Er is een ongeldig argument opgegeven. |
| TooManyOpenSockets | 10024 | Er zijn te veel geopende sockets in de onderliggende socketprovider. |
| WouldBlock | 10035 | Een bewerking kan niet onmiddellijk worden voltooid op een niet-blokkerende socket. |
| InProgress | 10036 | Een blokkerende bewerking is bezig. |
| AlreadyInProgress | 10037 | Een niet-blokkerende socket heeft al een lopende bewerking. |
| NotSocket | 10038 | Een poging om een socketbewerking aan te roepen op een niet-socket. |
| DestinationAddressRequired | 10039 | Een vereiste adres is weggelaten bij een socketbewerking. |
| MessageSize | 10040 | Een datagram is te lang. |
| ProtocolType | 10041 | Een protocoltype wordt niet ondersteund door deze socket. |
| ProtocolOption | 10042 | Er wordt een onbekende, ongeldige of niet-ondersteunde optie of niveau gebruikt. |
| ProtocolNotSupported | 10043 | Een protocol is niet geïmplementeerd of niet geconfigureerd. |
| SocketNotSupported | 10044 | Een adresfamilie ondersteunt de opgegeven socket niet. |
| OperationNotSupported | 10045 | Een protocolfamilie ondersteunt een adresfamilie niet. |
| ProtocolFamilyNotSupported | 10046 | Een protocolfamilie is niet geïmplementeerd of niet geconfigureerd. |
| AddressFamilyNotSupported | 10047 | De opgegeven adresfamilie wordt niet ondersteund. |
| AddressAlreadyInUse | 10048 | Een adres kan slechts één keer worden gebruikt. |
| AddressNotAvailable | 10049 | Het geselecteerde IP-adres is niet geldig in deze context. |
| NetworkDown | 10050 | Het netwerk is niet beschikbaar. |
| NetworkUnreachable | 10051 | Er bestaat geen route naar de externe host. |
| NetworkReset | 10052 | Een toepassing probeerde ‘Keep-Alive’ in te stellen op een verbinding die al is verlopen. |
| ConnectionAborted | 10053 | Een verbinding is afgebroken. |
| ConnectionReset | 10054 | Een verbinding is gereset door een externe peer. |
| NoBufferSpaceAvailable | 10055 | Er is geen vrije bufferruimte beschikbaar voor een socketbewerking. |
| IsConnected | 10056 | Een socket is al verbonden. |
| NotConnected | 10057 | Een toepassing probeerde data te verzenden of ontvangen, maar een socket is niet verbonden. |
| Shutdown | 10058 | Een verzoek om data te verzenden of ontvangen is verboden omdat de socket al is gesloten. |
| TimedOut | 10060 | Een verbindingspoging liep uit op tijd, of een verbonden host heeft niet gereageerd. |
| ConnectionRefused | 10061 | Een externe host weigert actief een verbinding. |
| HostDown | 10064 | Een bewerking mislukte omdat een externe host offline is. |
| HostUnreachable | 10065 | Er bestaat geen netwerkroute naar de opgegeven host. |
| ProcessLimit | 10067 | Te veel processen gebruiken de onderliggende socketprovider. |
| SystemNotReady | 10091 | Een netwerksubysteem is niet beschikbaar. |
| VersionNotSupported | 10092 | Een versie van de onderliggende socketprovider valt buiten het bereik. |
| NotInitialized | 10093 | De onderliggende socketprovider is niet geïnitialiseerd. |
| Disconnecting | 10101 | Een nette afsluiting is in uitvoering. |
| TypeNotFound | 10109 | De opgegeven klasse is niet gevonden. |
| HostNotFound | 11001 | De opgegeven host is onbekend. |
| TryAgain | 11002 | Een hostnaam kan niet worden opgelost. |
| NoRecovery | 11003 | Een fout is niet herstelbaar of een gevraagde database kan niet worden gevonden. |
| NoData | 11004 | Een gevraagde naam of IP-adres is niet gevonden op de naamserver. |

## Zie ook

* Naamruimte [System::Net::Sockets](../)
* Bibliotheek [Aspose.Slides](../../)