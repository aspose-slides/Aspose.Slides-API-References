---
title: set_HideTop()
second_title: Référence de l'API Aspose.Slides pour C++
description: Masquer le bord supérieur (false par défaut) - spécifie l'état masqué ou affiché du bord supérieur de la boîte de bordure.
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/imathborderbox/set_hidetop/
---
## IMathBorderBox::set_HideTop(bool) méthode

Masquer le bord supérieur (par défaut est false) - spécifie l'état masqué ou affiché du bord supérieur de la boîte de bordure.

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_HideTop(bool value)=0
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