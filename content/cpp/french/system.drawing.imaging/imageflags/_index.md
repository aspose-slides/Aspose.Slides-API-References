---
title: ImageFlags
second_title: Référence API Aspose.Slides pour C++
description: Représente les attributs des données de pixel représentées par un objet Image.
type: docs
weight: 274
url: /fr/system.drawing.imaging/imageflags/
---
## ImageFlags enum


Représente les attributs des données de pixel représentées par un objet [Image](../../system.drawing/image/).

```cpp
enum class ImageFlags
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Scalable. |
| HasAlpha | 2 | Contient les informations alpha. |
| HasTranslucent | 4 | Il existe des valeurs alpha supérieures à 0 et inférieures à 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | Les données de pixel sont représentées dans l'espace couleur RGB. |
| ColorSpaceCmyk | 32 | Les données de pixel sont représentées dans l'espace couleur CMYK. |
| ColorSpaceGray | 64 | Les données de pixel sont en niveaux de gris. |
| ColorSpaceYcbcr | 128 | Les données de pixel sont représentées dans l'espace couleur YCBCR. |
| ColorSpaceYcck | 256 | Les données de pixel sont représentées dans l'espace couleur YCCK. |
| HasRealDpi | 4096 | Les informations DPI sont stockées dans l'image. |
| HasRealPixelSize | 8192 | La taille d'un pixel est stockée dans l'image. |
| ReadOnly | 65536 | Les données de pixel sont en lecture seule. |
| Caching | 131072 | Peut être mis en cache pour un accès plus rapide. |

## Voir aussi

* Espace de noms [System::Drawing::Imaging](../)
* Bibliothèque [Aspose.Slides](../../)