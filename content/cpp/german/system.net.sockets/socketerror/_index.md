---
title: SocketError
second_title: Aspose.Slides für C++ API-Referenz
description: Enumeriert die Socket-Fehlertypen.
type: docs
weight: 209
url: /de/system.net.sockets/socketerror/
---
## SocketError Enum

Enumeriert die Socket-Fehlertypen.

```cpp
enum class SocketError
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Success | 0 | Ein Socket-Vorgang wurde erfolgreich abgeschlossen. |
| SocketError | -1 | Ein nicht spezifizierter Socket-Fehler ist aufgetreten. |
| Interrupted | 10004 | Ein blockierender Socket-Aufruf wurde abgebrochen. |
| AccessDenied | 10013 | Zugriff auf einen Socket wurde verweigert. |
| Fault | 10014 | Eine ungültige Zeigeradresse wurde festgestellt. |
| InvalidArgument | 10022 | Ein ungültiges Argument wurde übergeben. |
| TooManyOpenSockets | 10024 | Es gibt zu viele offene Sockets im zugrunde liegenden Socket-Provider. |
| WouldBlock | 10035 | Eine Operation kann auf einem nicht blockierenden Socket nicht sofort abgeschlossen werden. |
| InProgress | 10036 | Eine blockierende Operation ist im Gange. |
| AlreadyInProgress | 10037 | Ein nicht blockierender Socket hat bereits eine laufende Operation. |
| NotSocket | 10038 | Ein Versuch, eine Socket-Operation auf einem Nicht-Socket aufzurufen. |
| DestinationAddressRequired | 10039 | Eine erforderliche Adresse wurde bei einer Socket-Operation weggelassen. |
| MessageSize | 10040 | Ein Datagramm ist zu lang. |
| ProtocolType | 10041 | Ein Protokolltyp wird von diesem Socket nicht unterstützt. |
| ProtocolOption | 10042 | Eine unbekannte, ungültige oder nicht unterstützte Option bzw. Ebene wird verwendet. |
| ProtocolNotSupported | 10043 | Ein Protokoll ist nicht implementiert oder nicht konfiguriert. |
| SocketNotSupported | 10044 | Eine Adressfamilie unterstützt den angegebenen Socket nicht. |
| OperationNotSupported | 10045 | Eine Protokollfamilie unterstützt keine Adressfamilie. |
| ProtocolFamilyNotSupported | 10046 | Eine Protokollfamilie ist nicht implementiert oder nicht konfiguriert. |
| AddressFamilyNotSupported | 10047 | Die angegebene Adressfamilie wird nicht unterstützt. |
| AddressAlreadyInUse | 10048 | Eine Adresse kann nur einmal verwendet werden. |
| AddressNotAvailable | 10049 | Die ausgewählte IP-Adresse ist in diesem Kontext nicht gültig. |
| NetworkDown | 10050 | Das Netzwerk ist nicht verfügbar. |
| NetworkUnreachable | 10051 | Keine Route zum Remote-Host existiert. |
| NetworkReset | 10052 | Eine Anwendung versuchte, 'Keep-Alive' für eine Verbindung zu setzen, die bereits abgelaufen ist. |
| ConnectionAborted | 10053 | Eine Verbindung wurde abgebrochen. |
| ConnectionReset | 10054 | Eine Verbindung wurde von einem Remote-Partner zurückgesetzt. |
| NoBufferSpaceAvailable | 10055 | Kein freier Pufferplatz ist für eine Socket-Operation verfügbar. |
| IsConnected | 10056 | Ein Socket ist bereits verbunden. |
| NotConnected | 10057 | Eine Anwendung versuchte, Daten zu senden oder zu empfangen, und ein Socket ist nicht verbunden. |
| Shutdown | 10058 | Eine Anforderung zum Senden oder Empfangen von Daten ist verboten, weil der Socket bereits geschlossen wurde. |
| TimedOut | 10060 | Ein Verbindungsversuch ist abgelaufen, oder ein verbundener Host hat nicht geantwortet. |
| ConnectionRefused | 10061 | Ein Remote-Host verweigert aktiv eine Verbindung. |
| HostDown | 10064 | Eine Operation schlug fehl, weil ein Remote-Host ausgefallen ist. |
| HostUnreachable | 10065 | Keine Netzwerkroute zum angegebenen Host existiert. |
| ProcessLimit | 10067 | Zu viele Prozesse verwenden den zugrunde liegenden Socket-Provider. |
| SystemNotReady | 10091 | Ein Netzwerk-Subsystem ist nicht verfügbar. |
| VersionNotSupported | 10092 | Eine Version des zugrunde liegenden Socket-Providers liegt außerhalb des zulässigen Bereichs. |
| NotInitialized | 10093 | Der zugrunde liegende Socket-Provider ist nicht initialisiert. |
| Disconnecting | 10101 | Ein geordneter Shutdown ist im Gange. |
| TypeNotFound | 10109 | Die angegebene Klasse wurde nicht gefunden. |
| HostNotFound | 11001 | Der angegebene Host ist unbekannt. |
| TryAgain | 11002 | Ein Hostname kann nicht aufgelöst werden. |
| NoRecovery | 11003 | Ein Fehler ist nicht wiederherstellbar oder die angeforderte Datenbank kann nicht gefunden werden. |
| NoData | 11004 | Ein angeforderter Name oder eine IP-Adresse wurde nicht im Nameserver gefunden. |

## Siehe auch

* Namensraum [System::Net::Sockets](../)
* Bibliothek [Aspose.Slides](../../)