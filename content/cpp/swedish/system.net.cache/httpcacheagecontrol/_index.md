---
title: HttpCacheAgeControl
second_title: Aspose.Slides för C++ API-referens
description: CacheAgeControl används för att ange preferenser med avseende på cachelagda objekts ålder och färskhet.
type: docs
weight: 53
url: /sv/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum

CacheAgeControl används för att ange preferenser med avseende på cachelagda objekts ålder och färskhet.

```cpp
enum class HttpCacheAgeControl
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Endast för internt bruk. |
| MinFresh | 1 | Innehåll kan hämtas från cachen om den återstående tiden innan utgång är större än eller lika med den tid som anges med detta värde. |
| MaxAge | 2 | Innehåll kan hämtas från cachen tills det är äldre än den ålder som anges med detta värde. |
| MaxStale | 4 | Innehåll kan hämtas från cachen efter att det har löpt ut tills den tid som anges med detta värde har förflutit. |
| MaxAgeAndMinFresh | 3 | MaxAge and MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge and MaxStale. |

## Se också

* Namnrymd [System::Net::Cache](../)
* Bibliotek [Aspose.Slides](../../)