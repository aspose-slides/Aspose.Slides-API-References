---
title: RequestCacheLevel
second_title: Aspose.Slides voor C++ API-referentie
description: De enum beschrijft cache-instellingen die van toepassing zijn op elke WebRequest.
type: docs
weight: 27
url: /nl/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enum

De enum beschrijft cache-instellingen die van toepassing zijn op elke [WebRequest](../../system.net/webrequest/).

```cpp
enum class RequestCacheLevel
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Default | 0 | Vervult een verzoek om een bron, hetzij door de gecachte kopie van de bron te gebruiken, hetzij door een verzoek voor de bron naar de server te sturen. |
| BypassCache | 1 | Vervult een verzoek door de server te gebruiken. Er worden geen items uit de cache gehaald. |
| CacheOnly | 2 | Vervult een verzoek om een bron uitsluitend vanuit de cache. Een WebException wordt gegooid wanneer een bron niet in de clientcache aanwezig is. |
| CacheIfAvailable | 3 | Vervult een verzoek om een bron vanuit de cache als de bron beschikbaar is, anders wordt een verzoek naar de server gestuurd. |
| Revalidate | 4 | Gebruikt een lokale kopie van een bron als de tijdstempel van de client gelijk is aan de tijdstempel van de bron op de server. Anders wordt een bron van de server gedownload. |
| Reload | 5 | Een bron wordt altijd van de server gedownload. |
| NoCacheNoStore | 6 | Vervult nooit een verzoek door bronnen uit de cache te gebruiken en slaat bronnen niet op in de cache. |

## Zie ook

* Namespace [System::Net::Cache](../)
* Bibliotheek [Aspose.Slides](../../)