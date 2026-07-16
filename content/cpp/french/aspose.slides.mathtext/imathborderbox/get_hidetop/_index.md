---
title: get_HideTop()
second_title: Référence de l'API Aspose.Slides pour C++
description: Masquer le bord supérieur (par défaut est false) - spécifie l’état masqué ou affiché du bord supérieur de la boîte de bordure.
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/imathborderbox/get_hidetop/
---
## IMathBorderBox::get_HideTop() méthode


Masquer le bord supérieur (par défaut est false) - spécifie l’état masqué ou affiché du bord supérieur de la boîte de bordure.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideTop()=0
```

## Remarques


Exemple :
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideTop(true);
```

## Voir aussi

* Classe [IMathBorderBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)