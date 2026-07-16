---
title: HttpCacheAgeControl
second_title: Référence de l'API Aspose.Slides pour C++
description: CacheAgeControl est utilisé pour spécifier les préférences concernant l'âge et la fraîcheur des éléments mis en cache.
type: docs
weight: 53
url: /fr/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum

CacheAgeControl est utilisé pour spécifier les préférences concernant l'âge et la fraîcheur des éléments mis en cache.

```cpp
enum class HttpCacheAgeControl
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | À usage interne uniquement. |
| MinFresh | 1 | Le contenu peut être récupéré du cache si le temps restant avant l'expiration est supérieur ou égal au temps spécifié par cette valeur. |
| MaxAge | 2 | Le contenu peut être récupéré du cache tant qu'il n'est pas plus ancien que l'âge spécifié par cette valeur. |
| MaxStale | 4 | Le contenu peut être récupéré du cache après son expiration jusqu'à ce que le temps spécifié par cette valeur se soit écoulé. |
| MaxAgeAndMinFresh | 3 | MaxAge et MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge et MaxStale. |

## Voir aussi

* Espace de noms [System::Net::Cache](../)
* Bibliothèque [Aspose.Slides](../../)