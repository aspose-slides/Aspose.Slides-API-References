---
title: HttpRequestCacheLevel
second_title: Aspose.Slides for C++ API Referansı
description: HTTP için önbellek ayarlarını tanımlayan enum.
type: docs
weight: 40
url: /tr/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enum

Enum, HTTP için önbellek ayarlarını tanımlamaktadır.

```cpp
enum class HttpRequestCacheLevel
```

### Values

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Default | 0 | Bir kaynağa yönelik isteği, kaynağın önbellekteki kopyasını kullanarak veya isteği sunucuya göndererek karşılar. |
| BypassCache | 1 | İsteği sunucuyu kullanarak karşılar. |
| CacheOnly | 2 | Her zaman bir kaynağı almak için istemci önbelleğini kullanır. |
| CacheIfAvailable | 3 | Kaynak mevcutsa, isteği önbellekten karşılar; aksi takdirde isteği sunucuya gönderir. |
| Revalidate | 4 | İstemci zaman damgası sunucudaki kaynak zaman damgası ile aynıysa, yerel kopya kullanılır. Aksi takdirde, kaynak sunucudan indirilir. |
| Reload | 5 | Bir kaynak her zaman sunucudan indirilir. |
| NoCacheNoStore | 6 | İstek asla önbellekten alınan kaynaklarla karşılanmaz ve kaynaklar önbelleğe alınmaz. |
| CacheOrNextCacheOnly | 7 | Bir kaynağa yönelik isteği, yerel bilgisayarın önbelleğinden veya LAN üzerindeki uzak bir önbellekten karşılar. |
| Refresh | 8 | İsteği, sunucuyu veya yerel önbellek dışındaki bir önbelleği kullanarak karşılar. |

## İlgili

* Ad alanı [System::Net::Cache](../)
* Kütüphane [Aspose.Slides](../../)