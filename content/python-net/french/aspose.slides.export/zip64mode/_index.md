---
title: Zip64Mode enumeration
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/zip64mode/
---
## Zip64Mode énumération

Spécifie quand utiliser les extensions de format ZIP64 pour le fichier OpenXML.

Le type Zip64Mode expose les membres suivants :

## Champs

| Champ | Description |
| :- | :- |
| NEVER | Ne pas utiliser les extensions de format ZIP64. |
| IF_NECESSARY | Utiliser les extensions de format ZIP64 si nécessaire. |
| ALWAYS | Toujours utiliser les extensions de format ZIP64. |

### Remarques

Le fichier OpenXML est une archive ZIP qui a une limite de 4 GB (2^32 octets) sur la taille non compressée d'un fichier, la taille compressée d'un fichier et la taille totale de l'archive, ainsi qu'une limite de 65,535 (2^16-1) fichiers dans l'archive. Les extensions de format ZIP64 augmentent les limites à 2^64.

### Voir aussi
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)