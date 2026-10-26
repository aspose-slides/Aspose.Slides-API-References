---
title: HttpRequestCacheLevel
second_title: Aspose.Slides C++ API-referencia
description: Az enumeráció leírja a HTTP gyorsítótár beállításait.
type: docs
weight: 40
url: /hu/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enumeráció


Az enumeráció HTTP gyorsítótár beállításait írja le.

```cpp
enum class HttpRequestCacheLevel
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Default | 0 | Az erőforrásra vonatkozó kérést vagy a gyorsítótárban lévő másolat felhasználásával, vagy a szerverhez küldött kérés révén teljesíti. |
| BypassCache | 1 | A kérést a szerver használatával teljesíti. |
| CacheOnly | 2 | Mindig a kliens gyorsítótárát használja az erőforrás lekéréséhez. |
| CacheIfAvailable | 3 | Az erőforrásra vonatkozó kérést a gyorsítótárból teljesíti, ha az elérhető, egyébként a szerverhez küldi a kérést. |
| Revalidate | 4 | A helyi másolatot használja, ha a kliens időbélyege megegyezik a szerveren lévő erőforrás időbélyegével. Ellenkező esetben az erőforrás letöltődik a szerverről. |
| Reload | 5 | Az erőforrás mindig a szerverről kerül letöltésre. |
| NoCacheNoStore | 6 | Soha nem teljesíti a kérést a gyorsítótárból származó erőforrások használatával, és nem tárolja az erőforrásokat a gyorsítótárban. |
| CacheOrNextCacheOnly | 7 | Az erőforrásra vonatkozó kérést vagy a helyi számítógép gyorsítótárából, vagy egy távoli LAN gyorsítótárból teljesíti. |
| Refresh | 8 | A kérést a szerver vagy a helyi gyorsítótáron kívüli gyorsítótár használatával teljesíti. |

## Lásd még

* Névtér [System::Net::Cache](../)
* Könyvtár [Aspose.Slides](../../)