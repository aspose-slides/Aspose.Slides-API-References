---
title: set_HideBottom()
second_title: Référence de l'API Aspose.Slides pour C++
description: Masquer le bord inférieur (valeur par défaut false) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure.
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/imathborderbox/set_hidebottom/
---
## IMathBorderBox::set_HideBottom(bool) méthode

Masquer le bord inférieur (default is false) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure.

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_HideBottom(bool value)=0
```

## Remarques

Exemple :
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideBottom(true);
```

## Voir aussi

* Classe [IMathBorderBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)