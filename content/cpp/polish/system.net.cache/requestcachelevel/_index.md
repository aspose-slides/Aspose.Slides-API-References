---
title: RequestCacheLevel
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wyliczenie opisuje ustawienia pamięci podręcznej stosowane dla dowolnego WebRequest.
type: docs
weight: 27
url: /pl/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enum

Wyliczenie opisuje ustawienia pamięci podręcznej stosowane dla dowolnego [WebRequest](../../system.net/webrequest/).

```cpp
enum class RequestCacheLevel
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Default | 0 | Spełnia żądanie zasobu, używając albo skopiowanej z pamięci podręcznej wersji zasobu, albo wysyłając żądanie zasobu do serwera. |
| BypassCache | 1 | Spełnia żądanie używając serwera. Żadne wpisy nie są pobierane z pamięci podręcznej. |
| CacheOnly | 2 | Spełnia żądanie zasobu wyłącznie z pamięci podręcznej. W przypadku, gdy zasób nie znajduje się w pamięci podręcznej klienta, zostanie zgłoszony WebException. |
| CacheIfAvailable | 3 | Spełnia żądanie zasobu z pamięci podręcznej, jeśli zasób jest dostępny; w przeciwnym razie wysyła żądanie do serwera. |
| Revalidate | 4 | Używa lokalnej kopii zasobu, jeśli znacznik czasu klienta jest taki sam jak znacznik czasu zasobu na serwerze. W przeciwnym razie zasób jest pobierany z serwera. |
| Reload | 5 | Zasób jest zawsze pobierany z serwera. |
| NoCacheNoStore | 6 | Nigdy nie spełnia żądania, używając zasobów z pamięci podręcznej i nie zapisuje zasobów w pamięci podręcznej. |

## Zobacz także

* Przestrzeń nazw [System::Net::Cache](../)
* Biblioteka [Aspose.Slides](../../)