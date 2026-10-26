---
title: BlackWhiteConversionMode
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit des options qui contrôlent la façon dont les images des diapositives seront converties en images bitonales.
type: docs
weight: 820
url: /fr/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum


Fournit des options qui contrôlent la façon dont les images des diapositives seront converties en images bitonales.

```cpp
enum class BlackWhiteConversionMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Default | 0 | Spécifie aucun algorithme de conversion. L'algorithme implémenté dans le codec TIFF sera utilisé. (Par défaut) |
| Dithering | 1 | Spécifie l'algorithme de tramage (Floyd-Steinberg). |
| DitheringFloydSteinberg | 2 | Spécifie l'algorithme de tramage Floyd-Steinberg. |
| Auto | 3 | Spécifie l'algorithme de seuil calculé automatiquement (Otsu). |
| AutoOtsu | 4 | Spécifie l'algorithme de seuil Otsu calculé automatiquement. |
| Threshold25 | 5 | Spécifie l'algorithme de seuil statique (25%). |
| Threshold50 | 6 | Spécifie l'algorithme de seuil statique (50%). |
| Threshold75 | 7 | Spécifie l'algorithme de seuil statique (75%). |

## See Also

* Espace de noms [Aspose::Slides::Export](../)
* Bibliothèque [Aspose.Slides](../../)