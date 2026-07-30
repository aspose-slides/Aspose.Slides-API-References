---
title: HttpCacheAgeControl
second_title: Aspose.Slides per C++ Riferimento API
description: CacheAgeControl viene utilizzato per specificare le preferenze relative all'età e alla freschezza degli elementi nella cache.
type: docs
weight: 53
url: /it/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum

CacheAgeControl viene utilizzato per specificare le preferenze relative all'età e alla freschezza degli elementi nella cache.

```cpp
enum class HttpCacheAgeControl
```

### Valori

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Solo per uso interno. |
| MinFresh | 1 | Il contenuto può essere prelevato dalla cache se il tempo rimanente prima della scadenza è maggiore o uguale al tempo specificato con questo valore. |
| MaxAge | 2 | Il contenuto può essere prelevato dalla cache finché non è più vecchio dell'età specificata con questo valore. |
| MaxStale | 4 | Il contenuto può essere prelevato dalla cache dopo la scadenza fino a quando non trascorre il tempo specificato con questo valore. |
| MaxAgeAndMinFresh | 3 | MaxAge e MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge e MaxStale. |

## Vedi anche

* Spazio dei nomi [System::Net::Cache](../)
* Libreria [Aspose.Slides](../../)