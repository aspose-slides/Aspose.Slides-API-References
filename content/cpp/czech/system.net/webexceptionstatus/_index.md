---
title: WebExceptionStatus
second_title: Aspose.Slides pro C++ API Reference
description: Vypisuje stavové kódy třídy WebException.
type: docs
weight: 651
url: /cs/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

Vypisuje stavové kódy třídy WebException.

```cpp
enum class WebExceptionStatus
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Success | 0 | Nebyly zaznamenány žádné chyby. |
| NameResolutionFailure | 1 | Služba řešení názvů nemohla rozpoznat název hostitele. |
| ConnectFailure | 2 | Vzdálený služební bod nemohl být kontaktován na úrovni transportu. |
| ReceiveFailure | 3 | Od vzdáleného serveru nebyla přijata kompletní odpověď. |
| SendFailure | 4 | Kompletní požadavek nemohl být odeslán na vzdálený server. |
| PipelineFailure | 5 | Požadavek byl pipelined požadavek a spojení bylo uzavřeno před přijetím odpovědi. |
| RequestCanceled | 6 | Požadavek byl zrušen nebo došlo k neklasifikovatelné chybě. |
| ProtocolError | 7 | Odpověď přijatá od serveru byla kompletní, ale indikovala chybu na úrovni protokolu. |
| ConnectionClosed | 8 | Spojení bylo předčasně uzavřeno. |
| TrustFailure | 9 | Serverový certifikát nemohl být ověřen. |
| SecureChannelFailure | 10 | Při navazování spojení pomocí SSL došlo k chybě. |
| ServerProtocolViolation | 11 | Odpověď serveru nebyla platnou HTTP odpovědí. |
| KeepAliveFailure | 12 | Spojení pro požadavek, který specifikuje hlavičku 'Keep-Alive', bylo neočekávaně uzavřeno. |
| Pending | 13 | Vnitřní asynchronní požadavek čeká. |
| Timeout | 14 | Během časového limitu požadavku nebyla přijata žádná odpověď. |
| ProxyNameResolutionFailure | 15 | Služba řešení názvů nemohla rozpoznat název proxy hostitele. |
| UnknownError | 16 | Došlo k výjimce neznámého typu. |
| MessageLengthLimitExceeded | 17 | Byla přijata zpráva, která překročila stanovený limit. |
| CacheEntryNotFound | 18 | Zadaná položka mezipaměti nebyla nalezena. |
| RequestProhibitedByCachePolicy | 19 | Požadavek nebyl povolen zásadou mezipaměti. |
| RequestProhibitedByProxy | 20 | Tento požadavek nebyl povolen proxy. |

## Viz také

* Jmenný prostor [System::Net](../)
* Knihovna [Aspose.Slides](../../)