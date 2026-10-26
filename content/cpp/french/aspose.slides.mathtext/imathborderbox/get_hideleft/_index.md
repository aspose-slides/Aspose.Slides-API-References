---
title: get_HideLeft()
second_title: Référence de l'API Aspose.Slides pour C++
description: Masquer le bord gauche (false par défaut) - spécifie l'état masqué ou affiché du bord gauche de la boîte de bordure.
type: docs
weight: 66
url: /fr/aspose.slides.mathtext/imathborderbox/get_hideleft/
---
## IMathBorderBox::get_HideLeft() méthode


Masquer le bord gauche (par défaut false) - spécifie l’état masqué ou affiché du bord gauche de la boîte de bordure.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideLeft()=0
```

## Remarques


Exemple :
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideLeft(true);
```

## Voir aussi

* Classe [IMathBorderBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)