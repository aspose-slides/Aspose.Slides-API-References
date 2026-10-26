---
title: set_HideLeft()
second_title: Référence de l'API Aspose.Slides pour C++
description: Masquer le bord gauche (valeur par défaut : false) - spécifie l'état masqué ou affiché du bord gauche de la boîte de bordure.
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/imathborderbox/set_hideleft/
---
## IMathBorderBox::set_HideLeft(bool) method


Masquer le bord gauche (valeur par défaut : false) - spécifie l'état masqué ou affiché du bord gauche de la boîte de bordure.

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_HideLeft(bool value)=0
```

## Remarques


Exemple:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideLeft(true);
```

## Voir aussi

* Classe [IMathBorderBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)