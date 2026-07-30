---
title: HttpRequestCacheLevel
second_title: Riferimento API di Aspose.Slides per C++
description: L'enumerazione descrive le impostazioni della cache per HTTP.
type: docs
weight: 40
url: /it/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enum

L'enumerazione descrive le impostazioni della cache per HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Default | 0 | Soddisfa una richiesta per una risorsa utilizzando la copia memorizzata nella cache della risorsa oppure inviando una richiesta per la risorsa al server. |
| BypassCache | 1 | Soddisfa una richiesta utilizzando il server. |
| CacheOnly | 2 | Utilizza sempre la cache client per ottenere una risorsa. |
| CacheIfAvailable | 3 | Soddisfa una richiesta per una risorsa dalla cache se la risorsa è disponibile, altrimenti invia una richiesta al server. |
| Revalidate | 4 | Utilizza una copia locale della risorsa se il timestamp del client è lo stesso del timestamp della risorsa sul server. Altrimenti, la risorsa viene scaricata da un server. |
| Reload | 5 | Una risorsa viene sempre scaricata dal server. |
| NoCacheNoStore | 6 | Non soddisfa mai una richiesta utilizzando risorse dalla cache e non memorizza le risorse nella cache. |
| CacheOrNextCacheOnly | 7 | Soddisfa una richiesta per una risorsa oppure dalla cache del computer locale oppure da una cache remota sulla LAN. |
| Refresh | 8 | Soddisfa una richiesta utilizzando il server o una cache diversa dalla cache locale. |

## Vedi anche

* Spazio dei nomi [System::Net::Cache](../)
* Libreria [Aspose.Slides](../../)