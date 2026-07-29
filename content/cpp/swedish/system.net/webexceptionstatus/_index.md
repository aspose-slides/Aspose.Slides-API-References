---
title: WebExceptionStatus
second_title: Aspose.Slides för C++ API-referens
description: Enumererar statuskoderna för WebException-klassen.
type: docs
weight: 651
url: /sv/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

Enumererar statuskoderna för WebException-klassen.

```cpp
enum class WebExceptionStatus
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Success | 0 | Inga fel inträffade. |
| NameResolutionFailure | 1 | Namnlösningstjänsten kunde inte lösa värdnamnet. |
| ConnectFailure | 2 | Den fjärranslutna tjänstepunkten kunde inte nås på transportnivå. |
| ReceiveFailure | 3 | Ett komplett svar mottogs inte från den fjärranslutna servern. |
| SendFailure | 4 | En komplett förfrågan kunde inte skickas till den fjärranslutna servern. |
| PipelineFailure | 5 | Förfrågan var en pipeline-förfrågan och anslutningen stängdes innan svaret mottogs. |
| RequestCanceled | 6 | Förfrågan avbröts eller ett oklassificerbart fel inträffade. |
| ProtocolError | 7 | Svaret som mottogs från servern var komplett men indikerade ett protokollnivåfel. |
| ConnectionClosed | 8 | Anslutningen stängdes för tidigt. |
| TrustFailure | 9 | Ett servercertifikat kunde inte valideras. |
| SecureChannelFailure | 10 | Ett fel inträffade när en anslutning upprättades med SSL. |
| ServerProtocolViolation | 11 | Serverns svar var inte ett giltigt HTTP-svar. |
| KeepAliveFailure | 12 | Anslutningen för en förfrågan som specificerar 'Keep-Alive'-rubriken stängdes oväntat. |
| Pending | 13 | En intern asynkron förfrågan är pågående. |
| Timeout | 14 | Inget svar mottogs under timeoutperioden för en förfrågan. |
| ProxyNameResolutionFailure | 15 | Namntjänsten kunde inte lösa upp proxyvärdens namn. |
| UnknownError | 16 | Ett undantag av okänd typ har inträffat. |
| MessageLengthLimitExceeded | 17 | Ett meddelande som översteg den angivna gränsen mottogs. |
| CacheEntryNotFound | 18 | Den angivna cacheposten hittades inte. |
| RequestProhibitedByCachePolicy | 19 | Förfrågan var inte tillåten av cachepolicyn. |
| RequestProhibitedByProxy | 20 | Denna förfrågan var inte tillåten av proxy. |

## Se även

* Namespace [System::Net](../)
* Bibliotek [Aspose.Slides](../../)