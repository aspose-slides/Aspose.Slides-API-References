---
title: EmbeddingLevel enumeration
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/embeddinglevel/
---
## EmbeddingLevel énumération

Représente les droits de licence pour l’incorporation de la police.

Le type EmbeddingLevel expose les membres suivants :

## Champs

| Field | Description |
| :- | :- |
| INSTALLABLE | Les polices avec ce paramètre indiquent qu’elles peuvent être incorporées et installées de façon permanente sur le système distant par une application.<br/> L’utilisateur du système distant acquiert les mêmes droits, obligations et licences pour cette police que l’acheteur original de la police,<br/> et est soumis au même contrat de licence d’utilisateur final, aux droits d’auteur, au brevet de design et/ou à la marque déposée que l’acheteur original. |
| RESTRICTED | Les polices qui n’ont que ce bit activé ne doivent pas être modifiées, incorporées ou échangées de quelque manière que ce soit sans d’abord obtenir la permission du propriétaire légal. |
| PREVIEW_PRINT | Lorsque ce bit est activé, la police peut être incorporée et chargée temporairement sur le système distant. Les documents contenant des polices Preview &<br/> Print doivent être ouverts en « lecture seule » ; aucune modification ne peut être appliquée au document. |
| EDITABLE | Lorsque ce bit est activé, la police peut être incorporée mais ne doit être installée temporairement que sur d’autres systèmes. Contrairement aux polices Preview &<br/> Print, les documents contenant des polices Editable peuvent être ouverts en lecture, l’édition est autorisée et les modifications peuvent être enregistrées. |
| NO_SUBSETTING | Lorsque ce bit est activé, la police ne peut pas être sous-ensemble avant d’être incorporée. D’autres restrictions d’incorporation spécifiées dans les bits 0-3 et 9 s’appliquent également. |
| BITMAP_ONLY | Lorsque ce bit est activé, seuls les bitmaps contenus dans la police peuvent être incorporés. Aucune donnée de tracé ne peut être incorporée. S’il n’y a aucun bitmap disponible dans la police,<br/> la police est alors considérée comme non incorporable et les services d’incorporation échoueront. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)