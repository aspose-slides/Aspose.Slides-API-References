---
title: set_JpegQuality()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. Écrivez uint8_t.
type: docs
weight: 196
url: /fr/aspose.slides.export/ipdfoptions/set_jpegquality/
---
## IPdfOptions::set_JpegQuality(uint8_t) méthode


Définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. Écrivez **uint8_t**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_JpegQuality(uint8_t value)=0
```

## Remarques


N’a d’effet que lorsqu’un document contient des images JPEG.

Utilisez cette propriété pour obtenir ou définir la qualité des images à l'intérieur d'un document lors de l'enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais une compression maximale et 100 signifie la meilleure qualité mais une compression minimale.

La valeur par défaut est **100**.
## Voir aussi

* Classe [IPdfOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)