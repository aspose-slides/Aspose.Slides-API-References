---
title: UriComponents
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente les composants URI.
type: docs
weight: 3212
url: /fr/system/uricomponents/
---
## UriComponents enum

Représente les composants URI.

```cpp
enum class UriComponents
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Scheme | 1 | Les données Scheme. |
| UserInfo | 2 | Les données UserInfo. |
| Host | 4 | Les données Host. |
| Port | 8 | Les données Port. |
| SchemeAndServer | n/a | Les données Scheme, Host et Port. |
| Path | 16 | Les données LocalPath. |
| Query | 32 | Les données Query. |
| PathAndQuery | n/a | Les données LocalPath et Query. |
| HttpRequestUrl | n/a | Les données Scheme, Host, Port, Query et LocalPath. |
| Fragment | 64 | Les données Fragment. |
| AbsoluteUri | n/a | Les données Scheme, Host, Port, Query, LocalPath et Fragment. |
| StrongPort | 128 | Les données Port ; si les données de port ne sont pas présentes dans le [Uri](../uri/) et qu’un port par défaut a été attribué au Scheme, le port par défaut est renvoyé ; s’il n’y a pas de port par défaut, -1 est renvoyé. |
| HostAndPort | n/a | Les données Host et Port ; si les données de port ne sont pas présentes dans le [Uri](../uri/) et qu’un port par défaut a été attribué au Scheme, le port par défaut est renvoyé. S’il n’y a pas de port par défaut, -1 est renvoyé. |
| StrongAuthority | n/a | Les données UserInfo, Host et Port. Si aucune donnée de port n’est présente dans le [Uri](../uri/) et qu’un port par défaut a été attribué au Scheme, le port par défaut est renvoyé. S’il n’y a pas de port par défaut, -1 est renvoyé. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Spécifie que le délimiteur doit être inclus. |
| SerializationInfoString | n/a | Le contexte complet [Uri](../uri/) nécessaire aux sérialiseurs [Uri](../uri/). Le contexte comprend la portée IPv6. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)