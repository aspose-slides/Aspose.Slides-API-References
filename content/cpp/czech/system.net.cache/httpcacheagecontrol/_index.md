---
title: HttpCacheAgeControl
second_title: Aspose.Slides pro referenční příručku API C++
description: CacheAgeControl se používá k určení preferencí ohledně stáří a čerstvosti položek v mezipaměti.
type: docs
weight: 53
url: /cs/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl výčet

CacheAgeControl se používá k určení preferencí ohledně stáří a čerstvosti položek v mezipaměti.

```cpp
enum class HttpCacheAgeControl
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Pouze pro interní použití. |
| MinFresh | 1 | Obsah může být získán z mezipaměti, pokud zbývající čas do vypršení je větší nebo roven času uvedenému touto hodnotou. |
| MaxAge | 2 | Obsah může být získán z mezipaměti, dokud není starší než věk uvedený touto hodnotou. |
| MaxStale | 4 | Obsah může být získán z mezipaměti po jeho vypršení, dokud neuplynou stanovené časové období uvedené touto hodnotou. |
| MaxAgeAndMinFresh | 3 | MaxAge a MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge a MaxStale. |

## Viz také

* Jmenný prostor [System::Net::Cache](../)
* Knihovna [Aspose.Slides](../../)