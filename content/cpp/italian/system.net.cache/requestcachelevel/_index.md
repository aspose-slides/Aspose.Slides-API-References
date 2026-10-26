---
title: RequestCacheLevel
second_title: Riferimento API di Aspose.Slides per C++
description: L'enum descrive le impostazioni di cache applicabili a qualsiasi WebRequest.
type: docs
weight: 27
url: /it/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enum


L'enum descrive le impostazioni di cache applicabili a qualsiasi [WebRequest](../../system.net/webrequest/).

```cpp
enum class RequestCacheLevel
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Default | 0 | Soddisfa una richiesta per una risorsa utilizzando la copia in cache della risorsa o inviando una richiesta per la risorsa al server. |
| BypassCache | 1 | Soddisfa una richiesta utilizzando il server. Nessuna voce viene prelevata dalla cache. |
| CacheOnly | 2 | Soddisfa una richiesta per una risorsa solo dalla cache. Viene generata una WebException quando una risorsa non è presente nella cache client. |
| CacheIfAvailable | 3 | Soddisfa una richiesta per una risorsa dalla cache se la risorsa è disponibile, altrimenti invia una richiesta al server. |
| Revalidate | 4 | Utilizza una copia locale della risorsa se il timestamp del client è lo stesso del timestamp della risorsa sul server. In caso contrario, la risorsa viene scaricata da un server. |
| Reload | 5 | Una risorsa viene sempre scaricata dal server. |
| NoCacheNoStore | 6 | Non soddisfa mai una richiesta utilizzando risorse dalla cache e non memorizza le risorse nella cache. |

## Vedi anche

* Spazio dei nomi [System::Net::Cache](../)
* Libreria [Aspose.Slides](../../)