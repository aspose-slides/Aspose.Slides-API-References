---
title: HttpRequestCacheLevel
second_title: Aspose.Slides voor C++ API-referentie
description: De enum beschrijft cache-instellingen voor HTTP.
type: docs
weight: 40
url: /nl/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enum


De enum beschrijft cache-instellingen voor HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Default | 0 | Vervult een verzoek om een bron door ofwel de gecachte kopie van de bron te gebruiken of door een verzoek voor de bron naar de server te sturen. |
| BypassCache | 1 | Vervult een verzoek door de server te gebruiken. |
| CacheOnly | 2 | Gebruikt altijd de clientcache om een bron op te halen. |
| CacheIfAvailable | 3 | Vervult een verzoek om een bron uit de cache als de bron beschikbaar is; anders wordt een verzoek naar de server gestuurd. |
| Revalidate | 4 | Gebruikt een lokale kopie van de bron als de client-tijdstempel hetzelfde is als de tijdstempel van de bron op de server. Anders wordt de bron van een server gedownload. |
| Reload | 5 | Een bron wordt altijd van de server gedownload. |
| NoCacheNoStore | 6 | Vervult nooit een verzoek door bronnen uit de cache te gebruiken en slaat geen bronnen op in de cache. |
| CacheOrNextCacheOnly | 7 | Vervult een verzoek om een bron ofwel uit de cache van de lokale computer of uit een externe cache op het LAN. |
| Refresh | 8 | Vervult een verzoek door de server of een andere cache dan de lokale cache te gebruiken. |

## Zie ook

* Namespace [System::Net::Cache](../)
* Bibliotheek [Aspose.Slides](../../)