---
title: Zip64Mode
second_title: Référence API Aspose.Slides pour C++
description: Spécifie quand utiliser les extensions de format ZIP64 pour le fichier OpenXML.
type: docs
weight: 1119
url: /fr/aspose.slides.export/zip64mode/
---
## Zip64Mode énumération


Spécifie quand utiliser les extensions de format ZIP64 pour le fichier OpenXML.

```cpp
enum class Zip64Mode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Never | 0 | Ne pas utiliser les extensions de format ZIP64. |
| IfNecessary | 1 | Utiliser les extensions de format ZIP64 si nécessaire. |
| Always | 2 | Toujours utiliser les extensions de format ZIP64. |

## Remarques


Le fichier OpenXML est une archive ZIP qui a une limite de 4 GB (2^32 octets) sur la taille non compressée d’un fichier, la taille compressée d’un fichier et la taille totale de l’archive, ainsi qu’une limite de 65 535 (2^16-1) fichiers dans l’archive. Les extensions de format ZIP64 augmentent les limites à 2^64. 

## Voir aussi

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)