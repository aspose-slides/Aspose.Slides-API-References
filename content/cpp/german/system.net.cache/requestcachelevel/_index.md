---
title: RequestCacheLevel
second_title: Aspose.Slides für C++ API Referenz
description: Das Enum beschreibt Cache-Einstellungen, die für jede WebRequest gelten.
type: docs
weight: 27
url: /de/system.net.cache/requestcachelevel/
---
## RequestCacheLevel-Enum

Das Enum beschreibt Cache-Einstellungen, die für jedes [WebRequest](../../system.net/webrequest/) gelten.

```cpp
enum class RequestCacheLevel
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Default | 0 | Erfüllt eine Anforderung für eine Ressource entweder durch Verwendung der im Cache gespeicherten Kopie der Ressource oder indem eine Anforderung für die Ressource an den Server gesendet wird. |
| BypassCache | 1 | Erfüllt eine Anforderung, indem der Server verwendet wird. Es werden keine Einträge aus dem Cache genommen. |
| CacheOnly | 2 | Erfüllt eine Anforderung für eine Ressource ausschließlich aus dem Cache. Eine WebException wird ausgelöst, wenn sich eine Ressource nicht im Client-Cache befindet. |
| CacheIfAvailable | 3 | Erfüllt eine Anforderung für eine Ressource aus dem Cache, falls die Ressource verfügbar ist, andernfalls wird eine Anforderung an den Server gesendet. |
| Revalidate | 4 | Verwendet eine lokale Kopie einer Ressource, wenn der Zeitstempel des Clients mit dem Zeitstempel der Ressource auf dem Server übereinstimmt. Andernfalls wird die Ressource von einem Server heruntergeladen. |
| Reload | 5 | Eine Ressource wird immer vom Server heruntergeladen. |
| NoCacheNoStore | 6 | Erfüllt niemals eine Anforderung, indem Ressourcen aus dem Cache verwendet werden, und speichert keine Ressourcen im Cache. |

## Siehe auch

* Namensraum [System::Net::Cache](../)
* Bibliothek [Aspose.Slides](../../)