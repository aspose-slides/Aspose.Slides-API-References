---
title: CompressionLevel
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie les niveaux de compression ZIP pour les fichiers OpenXML. Les niveaux supérieurs offrent une meilleure compression au prix d'un traitement plus lent.
type: docs
weight: 846
url: /fr/aspose.slides.export/compressionlevel/
---
## CompressionLevel énumération

Spécifie les niveaux de compression ZIP pour les fichiers OpenXML. Les niveaux supérieurs offrent une meilleure compression au prix d’un traitement plus lent.

```cpp
enum class CompressionLevel
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Aucune compression n’est appliquée. Les fichiers sont stockés tels quels. |
| Level1 | 1 | Compression la plus rapide avec le rapport de compression le plus bas. |
| Level2 | 2 | Compression plus rapide avec un rapport de compression légèrement meilleur que [CompressionLevel::Level1](./). |
| Level3 | 3 | Offre une meilleure compression que [CompressionLevel::Level2](./) avec un impact modéré sur les performances. |
| Level4 | 4 | Offre une meilleure compression que [CompressionLevel::Level3](./). |
| Level5 | 5 | Offre une compression améliorée par rapport à [CompressionLevel::Level4](./) avec un temps de traitement supplémentaire. |
| Level6 | 6 | Compression standard, offrant un bon équilibre entre vitesse de compression et taille du fichier. Niveau de compression par défaut. |
| Level7 | 7 | Offre une compression supérieure à [CompressionLevel::Level6](./) avec un traitement plus lent. |
| Level8 | 8 | Offre une compression supérieure à [CompressionLevel::Level7](./). |
| Level9 | 9 | Compression maximale. Produit la plus petite taille de fichier avec la vitesse de traitement la plus lente. |

## Voir aussi

* Espace de noms [Aspose::Slides::Export](../)
* Bibliothèque [Aspose.Slides](../../)