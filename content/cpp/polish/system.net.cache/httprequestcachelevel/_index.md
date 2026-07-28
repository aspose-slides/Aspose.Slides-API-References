---
title: HttpRequestCacheLevel
second_title: Aspose.Slides dla C++ - referencja API
description: Enum opisuje ustawienia pamięci podręcznej dla HTTP.
type: docs
weight: 40
url: /pl/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enum


The enum describes cache settings for HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Values

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Default | 0 | Zaspokaja żądanie zasobu, używając albo skopiowanego w pamięci podręcznej zasobu, albo wysyłając żądanie zasobu do serwera. |
| BypassCache | 1 | Zaspokaja żądanie, używając serwera. |
| CacheOnly | 2 | Zawsze używa pamięci podręcznej klienta, aby uzyskać zasób. |
| CacheIfAvailable | 3 | Zaspokaja żądanie zasobu z pamięci podręcznej, jeśli zasób jest dostępny, w przeciwnym razie wysyła żądanie do serwera. |
| Revalidate | 4 | Używa lokalnej kopii zasobu, jeśli znacznik czasu klienta jest taki sam jak znacznik czasu zasobu na serwerze. W przeciwnym razie zasób jest pobierany z serwera. |
| Reload | 5 | Zasób jest zawsze pobierany z serwera. |
| NoCacheNoStore | 6 | Nigdy nie zaspokaja żądania, używając zasobów z pamięci podręcznej i nie zapisuje zasobów w pamięci podręcznej. |
| CacheOrNextCacheOnly | 7 | Zaspokaja żądanie zasobu albo z pamięci podręcznej lokalnego komputera, albo ze zdalnej pamięci podręcznej w sieci LAN. |
| Refresh | 8 | Zaspokaja żądanie, używając serwera lub pamięci podręcznej innej niż lokalna. |

## Zobacz także

* Przestrzeń nazw [System::Net::Cache](../)
* Biblioteka [Aspose.Slides](../../)