---
title: EmbeddingLevel
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente les droits de licence pour l'incorporation de la police.
type: docs
weight: 5786
url: /fr/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enum

Représente les droits de licence pour l'incorporation de la police.

```cpp
enum class EmbeddingLevel : uint16_t
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) avec ce paramètre indiquent qu'ils peuvent être incorporés et installés en permanence sur le système distant par une application. L'utilisateur du système distant acquiert les mêmes droits, obligations et licences pour cette police que l'acheteur original de la police, et est soumis au même contrat de licence utilisateur final, droit d'auteur, brevet de design et/ou marque que l'acheteur original. |
| Restricted | 2 | [Fonts](../fonts/) qui n'ont que ce bit activé ne doivent pas être modifiés, incorporés ou échangés de quelque manière que ce soit sans d'abord obtenir l'autorisation du propriétaire légal. |
| PreviewPrint | 4 | Lorsque ce bit est activé, la police peut être incorporée et chargée temporairement sur le système distant. Les documents contenant des polices Preview & Print doivent être ouverts en \"read-only;\" aucune modification ne peut être appliquée au document. |
| Editable | 8 | Lorsque ce bit est activé, la police peut être incorporée mais ne doit être installée que temporairement sur d'autres systèmes. Contrairement aux polices Preview & Print, les documents contenant des polices Editable peuvent être ouverts en lecture, l'édition est autorisée et les modifications peuvent être enregistrées. |
| NoSubsetting | 256 | Lorsque ce bit est activé, la police ne peut pas être sous-ensemble avant l'incorporation. D'autres restrictions d'incorporation spécifiées dans les bits 0-3 et 9 s'appliquent également. |
| BitmapOnly | 512 | Lorsque ce bit est activé, seuls les bitmaps contenus dans la police peuvent être incorporés. Aucune donnée de contour ne peut être incorporée. S'il n'y a aucun bitmap disponible dans la police, alors la police est considérée comme non incorporable et les services d'incorporation échoueront. |

## Voir aussi

* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)