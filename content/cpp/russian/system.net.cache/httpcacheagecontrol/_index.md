---
title: HttpCacheAgeControl
second_title: Aspose.Slides для C++ справочник API
description: CacheAgeControl используется для указания предпочтений в отношении возраста и актуальности кэшируемого элемента.
type: docs
weight: 53
url: /ru/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum

CacheAgeControl используется для указания предпочтений в отношении возраста и актуальности кэшируемого элемента.

```cpp
enum class HttpCacheAgeControl
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Только для внутреннего использования. |
| MinFresh | 1 | Содержимое может быть взято из кэша, если оставшееся время до истечения срока превышает или равно времени, указанному этим значением. |
| MaxAge | 2 | Содержимое может быть взято из кэша, пока его возраст не превысит возраст, указанный этим значением. |
| MaxStale | 4 | Содержимое может быть взято из кэша после его истечения, пока не истечёт время, указанное этим значением. |
| MaxAgeAndMinFresh | 3 | MaxAge и MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge и MaxStale. |

## См. также

* Пространство имён [System::Net::Cache](../)
* Библиотека [Aspose.Slides](../../)