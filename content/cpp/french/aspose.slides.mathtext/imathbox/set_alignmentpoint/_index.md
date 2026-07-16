---
title: set_AlignmentPoint()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Lorsque la valeur est true, cet émulateur d'opérateur sert de point d'alignement ; ainsi, les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. Par défaut : false"
type: docs
weight: 105
url: /fr/aspose.slides.mathtext/imathbox/set_alignmentpoint/
---
## IMathBox::set_AlignmentPoint(bool) méthode


Lorsque la valeur est true, cet emulateur d'opérateur sert de point d'alignement ; ainsi, les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. Par défaut : false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_AlignmentPoint(bool value)=0
```

## Remarques


Exemple : 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Voir aussi

* Classe [IMathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)