---
title: WebExceptionStatus
second_title: Aspose.Slides voor C++ API-referentie
description: Somt de statuscodes van de WebException-klasse op.
type: docs
weight: 651
url: /nl/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

Enumerates the status codes of the WebException class.

```cpp
enum class WebExceptionStatus
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Success | 0 | Er zijn geen fouten opgetreden. |
| NameResolutionFailure | 1 | De naamomzettingsservice kon de hostnaam niet oplossen. |
| ConnectFailure | 2 | Het externe servicepunt kon op transportniveau niet worden gecontacteerd. |
| ReceiveFailure | 3 | Er wordt geen volledige respons ontvangen van de externe server. |
| SendFailure | 4 | Een volledig verzoek kon niet naar de externe server worden verzonden. |
| PipelineFailure | 5 | Het verzoek was een gepijplined verzoek en de verbinding werd gesloten voordat de respons werd ontvangen. |
| RequestCanceled | 6 | Het verzoek werd geannuleerd of er trad een niet-klasseerbare fout op. |
| ProtocolError | 7 | De van de server ontvangen respons was compleet maar gaf een fout op protocolniveau aan. |
| ConnectionClosed | 8 | De verbinding werd voortijdig gesloten. |
| TrustFailure | 9 | Een servercertificaat kon niet worden gevalideerd. |
| SecureChannelFailure | 10 | Er trad een fout op bij het tot stand brengen van een verbinding met SSL. |
| ServerProtocolViolation | 11 | De serverrespons was geen geldige HTTP-respons. |
| KeepAliveFailure | 12 | De verbinding voor een verzoek dat de 'Keep-Alive' header specificeert, werd onverwacht gesloten. |
| Pending | 13 | Een interne asynchrone aanvraag is in behandeling. |
| Timeout | 14 | Er werd geen respons ontvangen gedurende de timeout-periode voor een verzoek. |
| ProxyNameResolutionFailure | 15 | De naamomzettingsservice kon de proxy-hostnaam niet oplossen. |
| UnknownError | 16 | Er is een uitzondering van onbekend type opgetreden. |
| MessageLengthLimitExceeded | 17 | Er werd een bericht ontvangen dat de opgegeven limiet overschreed. |
| CacheEntryNotFound | 18 | De opgegeven cache-invoer werd niet gevonden. |
| RequestProhibitedByCachePolicy | 19 | Het verzoek werd niet toegestaan door het cache-beleid. |
| RequestProhibitedByProxy | 20 | Dit verzoek werd niet toegestaan door de proxy. |

## Zie ook

* Naamruimte [System::Net](../)
* Bibliotheek [Aspose.Slides](../../)