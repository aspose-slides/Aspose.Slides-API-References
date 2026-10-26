---
title: get_AlignmentPoint()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Lorsque true, cet émulateur d'opérateur sert de point d'alignement ; c'est-à-dire que les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. Valeur par défaut : false"
type: docs
weight: 92
url: /fr/aspose.slides.mathtext/imathbox/get_alignmentpoint/
---
## IMathBox::get_AlignmentPoint() méthode

Lorsque true, cet émulateur d'opérateur sert de point d'alignement ; c'est a dire que les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. Valeur par défaut: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_AlignmentPoint()=0
```

## Remarques

Exemple: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Voir aussi

* Classe [IMathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)