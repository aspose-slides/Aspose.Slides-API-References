---
title: get_AlignmentPoint()
second_title: Référence API Aspose.Slides pour C++
description: "Lorsque true, cet émulateur d'operateur sert de point d'alignement; c'est a dire que les points d'alignement designes dans d'autres equations peuvent etre aligns avec lui. Par defaut: false"
type: docs
weight: 92
url: /fr/aspose.slides.mathtext/mathbox/get_alignmentpoint/
---
## MathBox::get_AlignmentPoint() méthode


Lorsque true, cet émulateur d'opérateur sert de point d'alignement; c’est-à-dire que les points d'alignement désignés dans d’autres équations peuvent être alignés avec lui. Par défaut: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_AlignmentPoint() override
```

## Remarques


Exemple: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Voir aussi

* Classe [MathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)