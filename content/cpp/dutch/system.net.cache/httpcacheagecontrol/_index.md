---
title: HttpCacheAgeControl
second_title: Aspose.Slides voor C++ API-referentie
description: CacheAgeControl wordt gebruikt om voorkeuren met betrekking tot de leeftijd en versheid van gecachte items op te geven.
type: docs
weight: 53
url: /nl/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum

CacheAgeControl wordt gebruikt om voorkeuren met betrekking tot de leeftijd en versheid van gecachte items op te geven.

```cpp
enum class HttpCacheAgeControl
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | 0 | Alleen voor intern gebruik. |
| MinFresh | 1 | Inhoud kan uit de cache worden gehaald als de resterende tijd vóór vervaldatum groter dan of gelijk is aan de tijd die met deze waarde is gespecificeerd. |
| MaxAge | 2 | Inhoud kan uit de cache worden gehaald totdat deze ouder is dan de leeftijd die met deze waarde is gespecificeerd. |
| MaxStale | 4 | Inhoud kan uit de cache worden gehaald nadat deze verlopen is, tot de tijd die met deze waarde is opgegeven verstrijkt. |
| MaxAgeAndMinFresh | 3 | MaxAge and MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge and MaxStale. |

## Zie ook

* Namespace [System::Net::Cache](../)
* Library [Aspose.Slides](../../)