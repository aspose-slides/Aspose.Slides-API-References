---
title: HttpCacheAgeControl
second_title: Aspose.Slides için C++ API Referansı
description: CacheAgeControl, önbelleğe alınmış öğenin yaşı ve tazeliğiyle ilgili tercihleri belirtmek için kullanılır.
type: docs
weight: 53
url: /tr/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum


CacheAgeControl, önbelleğe alınmış öğenin yaşı ve tazeliğiyle ilgili tercihleri belirtmek için kullanılır.

```cpp
enum class HttpCacheAgeControl
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | 0 | Yalnızca dahili kullanım için. |
| MinFresh | 1 | Önbellekten alınan içerik, süresi dolmadan kalan zaman bu değerle belirtilen süreden büyük veya eşitse alınabilir. |
| MaxAge | 2 | Önbellekten içerik, bu değerle belirtilen yaştan daha eski olana kadar alınabilir. |
| MaxStale | 4 | Önbellekten içerik, süresi dolduktan sonra bile bu değerle belirtilen zaman geçene kadar alınabilir. |
| MaxAgeAndMinFresh | 3 | MaxAge and MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge and MaxStale. |

## Ayrıca Bakınız

* Namespace [System::Net::Cache](../)
* Library [Aspose.Slides](../../)