---
title: WebExceptionStatus
second_title: Aspose.Slides C++ API referencia
description: Felsorolja a WebException osztály állapotkódjait.
type: docs
weight: 651
url: /hu/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

Felsorolja a WebException osztály állapotkódjait.

```cpp
enum class WebExceptionStatus
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Success | 0 | Nem történt hiba. |
| NameResolutionFailure | 1 | A névfeloldási szolgáltatás nem tudta feloldani a gép nevét. |
| ConnectFailure | 2 | A távoli szolgáltatás pont nem érhető el a szállítási szinten. |
| ReceiveFailure | 3 | A távoli szervertől nem érkezett teljes válasz. |
| SendFailure | 4 | A távoli szerverhez nem küldhető el teljes kérés. |
| PipelineFailure | 5 | A kérés pipelined kérés volt, és a kapcsolat a válasz érkezése előtt lezárult. |
| RequestCanceled | 6 | A kérés törölve lett vagy osztályozhatatlan hiba történt. |
| ProtocolError | 7 | A szervertől kapott válasz teljes volt, de protokoll szintű hibát jelzett. |
| ConnectionClosed | 8 | A kapcsolat túl korán lezárult. |
| TrustFailure | 9 | A szerver tanúsítványa nem hitelesíthető. |
| SecureChannelFailure | 10 | Hiba történt SSL-kapcsolat létesítése közben. |
| ServerProtocolViolation | 11 | A szerver válasza nem érvényes HTTP válasz volt. |
| KeepAliveFailure | 12 | A 'Keep-Alive' fejlécet tartalmazó kérés kapcsolata váratlanul lezárult. |
| Pending | 13 | Egy belső aszinkron kérés függőben van. |
| Timeout | 14 | A kéréshez tartozó időkorlát alatt nem érkezett válasz. |
| ProxyNameResolutionFailure | 15 | A névfeloldási szolgáltatás nem tudta feloldani a proxy gép nevét. |
| UnknownError | 16 | Ismeretlen típusú kivétel történt. |
| MessageLengthLimitExceeded | 17 | Egy üzenet érkezett, amely meghaladta a megadott korlátot. |
| CacheEntryNotFound | 18 | A megadott gyorsítótár bejegyzés nem található. |
| RequestProhibitedByCachePolicy | 19 | A kérés nem megengedett a gyorsítótár szabálya szerint. |
| RequestProhibitedByProxy | 20 | Ez a kérés nem engedélyezett a proxy által. |

## Lásd még

* Névtere [System::Net](../)
* Könyvtár [Aspose.Slides](../../)