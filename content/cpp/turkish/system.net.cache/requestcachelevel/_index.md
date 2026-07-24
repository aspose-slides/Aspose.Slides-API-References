---
title: RequestCacheLevel
second_title: Aspose.Slides for C++ API Referansı
description: Bu enum, herhangi bir WebRequest için geçerli olan önbellek ayarlarını tanımlar.
type: docs
weight: 27
url: /tr/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enum

The enum describes cache settings applicable for any [WebRequest](../../system.net/webrequest/).

```cpp
enum class RequestCacheLevel
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Default | 0 | Bir kaynağa yönelik isteği, kaynağın önbellekteki kopyasını kullanarak veya isteği sunucuya göndererek karşılar. |
| BypassCache | 1 | İsteği sunucuyu kullanarak karşılar. Önbellekten hiçbir girdi alınmaz. |
| CacheOnly | 2 | Bir kaynağa yönelik isteği yalnızca önbellekten karşılar. Kaynak istemci önbelleğinde bulunmadığında WebException fırlatılır. |
| CacheIfAvailable | 3 | Kaynak mevcut ise isteği önbellekten karşılar, aksi takdirde isteği sunucuya gönderir. |
| Revalidate | 4 | İstemci zaman damgası, sunucudaki kaynağın zaman damgası ile aynı ise yerel kopya kullanılır. Aksi takdirde kaynak sunucudan indirilir. |
| Reload | 5 | Bir kaynak her zaman sunucudan indirilir. |
| NoCacheNoStore | 6 | İstek hiçbir zaman önbellekten kaynak kullanılarak karşılanmaz ve kaynakları önbelleğe almaz. |

## Ayrıca Bakınız

* Ad Alanı [System::Net::Cache](../)
* Kütüphane [Aspose.Slides](../../)