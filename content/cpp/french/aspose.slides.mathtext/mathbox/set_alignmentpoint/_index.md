---
title: set_AlignmentPoint()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Lorsque vrai, cet émulateur d'opérateur sert de point d'alignement ; c'est-à-dire que les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. Valeur par défaut : false"
type: docs
weight: 105
url: /fr/aspose.slides.mathtext/mathbox/set_alignmentpoint/
---
## MathBox::set_AlignmentPoint(bool) méthode


Lorsque vrai, cet émulateur d'opérateur sert de point d'alignement ; c'est-à-dire que les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. Valeur par défaut : false

```cpp
void Aspose::Slides::MathText::MathBox::set_AlignmentPoint(bool value) override
```

## Remarques


Exemple :
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Voir aussi

* Classe [MathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)