---
title: HttpCacheAgeControl
second_title: Aspose.Slides C++ API hivatkozás
description: A CacheAgeControl a gyorsítótárazott elemek korával és frissességével kapcsolatos beállítások megadására szolgál.
type: docs
weight: 53
url: /hu/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enumeráció

CacheAgeControl arra szolgál, hogy meghatározza a gyorsítótárazott elemek korával és frissességével kapcsolatos beállításokat.

```cpp
enum class HttpCacheAgeControl
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| None | 0 | Csak belső használatra. |
| MinFresh | 1 | A tartalom a gyorsítótárból vehető, ha a lejáratig hátralévő idő nagyobb vagy egyenlő ezzel az értékkel megadott idővel. |
| MaxAge | 2 | A tartalom a gyorsítótárból vehető, amíg nem haladja meg a megadott értékkel meghatározott kort. |
| MaxStale | 4 | A tartalom a gyorsítótárból vehető a lejárása után is, amíg a megadott értékben meghatározott idő el nem telik. |
| MaxAgeAndMinFresh | 3 | MaxAge and MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge and MaxStale. |

## Lásd még

* Névtér [System::Net::Cache](../)
* Könyvtár [Aspose.Slides](../../)