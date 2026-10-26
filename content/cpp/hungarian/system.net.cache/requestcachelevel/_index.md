---
title: RequestCacheLevel
second_title: Aspose.Slides C++ API hivatkozás
description: Az enumeráció leírja a gyorsítótár beállításait, amelyek bármely WebRequest-re alkalmazhatók.
type: docs
weight: 27
url: /hu/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enum

Az enumeráció leírja a gyorsítótár beállításait, amelyek bármely [WebRequest](../../system.net/webrequest/)-ra alkalmazhatók.

```cpp
enum class RequestCacheLevel
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Default | 0 | Teljesíti a kérést egy erőforrásra úgy, hogy vagy a erőforrás gyorsítótárazott másolatát használja, vagy kérést küld a szervernek az erőforrásért. |
| BypassCache | 1 | A kérést a szerver használatával teljesíti. A gyorsítótárból semmilyen bejegyzés nem kerül felhasználásra. |
| CacheOnly | 2 | A kérést csak a gyorsítótárból teljesíti az erőforrásra vonatkozóan. WebException lesz dobva, ha egy erőforrás nincs a kliens gyorsítótárában. |
| CacheIfAvailable | 3 | A kérést egy erőforrásra a gyorsítótárból teljesíti, ha az erőforrás elérhető, egyébként kérést küld a szervernek. |
| Revalidate | 4 | Az erőforrás helyi másolatát használja, ha a kliens időbélyege megegyezik a szerveren lévő erőforrás időbélyegével. Egyébként az erőforrást a szerverről tölti le. |
| Reload | 5 | Az erőforrás mindig a szerverről töltődik le. |
| NoCacheNoStore | 6 | Soha nem teljesíti a kérést a gyorsítótárból származó erőforrások használatával, és nem gyorsítótárazza az erőforrásokat. |

## Lásd még

* Névtér [System::Net::Cache](../)
* Könyvtár [Aspose.Slides](../../)