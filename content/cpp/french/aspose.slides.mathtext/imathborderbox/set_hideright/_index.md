---
title: set_HideRight()
second_title: Référence de l'API Aspose.Slides pour C++
description: Masquer le bord droit (la valeur par défaut est false) - spécifie l'état masqué ou affiché du bord droit de la boîte de bordure.
type: docs
weight: 105
url: /fr/aspose.slides.mathtext/imathborderbox/set_hideright/
---
## IMathBorderBox::set_HideRight(bool) méthode

Masquer le bord droit (la valeur par défaut est false) - spécifie l'état masqué ou affiché du bord droit de la boîte de bordure.

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_HideRight(bool value)=0
```

## Remarques

Exemple:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideRight(true);
```

## Voir aussi

* Classe [IMathBorderBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)