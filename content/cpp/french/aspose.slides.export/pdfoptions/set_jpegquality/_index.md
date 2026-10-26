---
title: set_JpegQuality()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. Écrire uint8_t.
type: docs
weight: 235
url: /fr/aspose.slides.export/pdfoptions/set_jpegquality/
---
## PdfOptions::set_JpegQuality(uint8_t) méthode


Définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. Écrire **uint8_t**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_JpegQuality(uint8_t value) override
```

## Remarques


N'a d'effet que lorsqu'un document contient des images JPEG.

Utiliser cette propriété pour obtenir ou définir la qualité des images à l'intérieur d'un document lors de l'enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale.

La valeur par défaut est **100**.
## Voir aussi

* Classe [PdfOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)