---
title: HttpCacheAgeControl
second_title: Aspose.Slides dla C++ – dokumentacja API
description: CacheAgeControl jest używany do określania preferencji dotyczących wieku i aktualności elementu w pamięci podręcznej.
type: docs
weight: 53
url: /pl/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum

CacheAgeControl jest używany do określania preferencji dotyczących wieku i aktualności elementu w pamięci podręcznej.

```cpp
enum class HttpCacheAgeControl
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| None | 0 | Tylko do użytku wewnętrznego. |
| MinFresh | 1 | Treść może być pobrana z pamięci podręcznej, jeśli pozostały czas przed wygaśnięciem jest większy lub równy czasowi określonemu tą wartością. |
| MaxAge | 2 | Treść może być pobrana z pamięci podręcznej, dopóki nie będzie starsza niż wiek określony tą wartością. |
| MaxStale | 4 | Treść może być pobrana z pamięci podręcznej po jej wygaśnięciu, aż do upłynięcia czasu określonego tą wartością. |
| MaxAgeAndMinFresh | 3 | MaxAge i MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge i MaxStale. |

## Zobacz także

* Przestrzeń nazw [System::Net::Cache](../)
* Biblioteka [Aspose.Slides](../../)