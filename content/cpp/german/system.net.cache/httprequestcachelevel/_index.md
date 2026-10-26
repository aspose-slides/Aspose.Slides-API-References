---
title: HttpRequestCacheLevel
second_title: Aspose.Slides für C++ API-Referenz
description: Die Enum beschreibt die Cache-Einstellungen für HTTP.
type: docs
weight: 40
url: /de/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel Enum

Die Enum beschreibt die Cache-Einstellungen für HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Default | 0 | Erfüllt eine Anforderung für eine Ressource entweder durch Verwendung der zwischengespeicherten Kopie der Ressource oder indem eine Anforderung für die Ressource an den Server gesendet wird. |
| BypassCache | 1 | Erfüllt eine Anforderung durch Verwendung des Servers. |
| CacheOnly | 2 | Verwendet immer den Client-Cache, um eine Ressource zu erhalten. |
| CacheIfAvailable | 3 | Erfüllt eine Anforderung für eine Ressource aus dem Cache, wenn die Ressource verfügbar ist, andernfalls wird eine Anforderung an den Server gesendet. |
| Revalidate | 4 | Verwendet eine lokale Kopie einer Ressource, wenn der Zeitstempel des Clients mit dem Zeitstempel der Ressource auf dem Server übereinstimmt. Andernfalls wird die Ressource von einem Server heruntergeladen. |
| Reload | 5 | Eine Ressource wird immer vom Server heruntergeladen. |
| NoCacheNoStore | 6 | Erfüllt niemals eine Anforderung durch Verwendung von Ressourcen aus dem Cache und speichert Ressourcen nicht im Cache. |
| CacheOrNextCacheOnly | 7 | Erfüllt eine Anforderung für eine Ressource entweder aus dem Cache des lokalen Computers oder aus einem entfernten Cache im LAN. |
| Refresh | 8 | Erfüllt eine Anforderung durch Verwendung des Servers oder eines anderen Caches als des lokalen Caches. |

## Siehe Auch

* Namensraum [System::Net::Cache](../)
* Library [Aspose.Slides](../../)