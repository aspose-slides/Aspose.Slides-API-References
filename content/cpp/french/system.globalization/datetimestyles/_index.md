---
title: DateTimeStyles
second_title: Référence API Aspose.Slides pour C++
description: Définit les options de formatage de date et d'heure. Drapeaux de bits.
type: docs
weight: 456
url: /fr/system.globalization/datetimestyles/
---
## enum DateTimeStyles

Définit les options de formatage de date et d'heure. Drapeaux de bits.

```cpp
enum class DateTimeStyles : int32_t
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Par défaut. |
| AllowLeadingWhite | 1 | Ignorer les espaces blancs en début. |
| AllowTrailingWhite | 2 | Ignorer les espaces blancs en fin. |
| AllowInnerWhite | 4 | Ignorer les espaces blancs internes. |
| AllowWhiteSpaces | n/a | Ignorer tous les espaces blancs. |
| NoCurrentDateDefault | 8 | Lors de l'analyse d'une chaîne date/heure, si l'année/mois/jour sont tous absents, définir la date par défaut à 0001/1/1, au lieu de l'année/mois/jour actuel. |
| AdjustToUniversal | 16 | Lors de l'analyse d'une chaîne date/heure, si un spécificateur de fuseau horaire ("GMT","Z","+xxxx","-xxxx") existe, nous ajusterons l'heure analysée en fonction du GMT. |
| AssumeLocal | 32 | Si aucun fuseau horaire n'est fourni, utiliser le fuseau horaire local. |
| AssumeUniversal | 64 | Si aucun fuseau horaire n'est fourni, utiliser le UTC. |
| RoundtripKind | 128 | Essayer de préserver si l'entrée est non spécifiée, locale ou UTC. |

## Voir aussi

* Espace de noms [System::Globalization](../)
* Bibliothèque [Aspose.Slides](../../)