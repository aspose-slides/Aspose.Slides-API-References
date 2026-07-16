---
title: get_SufficientResolution()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une valeur déterminant la résolution des images dans le document PDF.
type: docs
weight: 352
url: /fr/aspose.slides.export/pdfoptions/get_sufficientresolution/
---
## PdfOptions::get_SufficientResolution() method


Renvoie une valeur déterminant la résolution des images dans le document PDF.

```cpp
float Aspose::Slides::Export::PdfOptions::get_SufficientResolution() override
```

## Remarques


La propriété affecte la taille du fichier, le temps d'exportation et la qualité de l'image.

La valeur par défaut est **96**.

L'effet de ce paramètre dépend de quelques facteurs. L'algorithme essaie d'obtenir la meilleure taille d'image de sortie en fonction de la valeur de la propriété, de la taille de l'image source et de la taille du cadre de l'image. L'utilisation de valeurs de propriété similaires peut donner le même résultat. Il est recommandé d'utiliser un pas de 16 ou 32 pour obtenir un effet visible.

Lire **float**. 
## Voir aussi

* Classe [PdfOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)