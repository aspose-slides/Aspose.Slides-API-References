---
title: get_StrikethroughBottomLeftToTopRight()
second_title: Référence de l'API Aspose.Slides pour C++
description: Barrer du coin inférieur gauche au coin supérieur droit (false par défaut). Spécifie l'état masqué ou affiché d'une ligne diagonale barrée du coin inférieur gauche au coin supérieur droit de la boîte de bordure.
type: docs
weight: 170
url: /fr/aspose.slides.mathtext/imathborderbox/get_strikethroughbottomlefttotopright/
---
## IMathBorderBox::get_StrikethroughBottomLeftToTopRight() méthode

Barrer du coin inférieur gauche au coin supérieur droit (par défaut est false). Spécifie l'état masqué ou affiché d'une ligne diagonale barrée du coin inférieur gauche au coin supérieur droit de la boîte de bordure.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughBottomLeftToTopRight()=0
```

## Remarques

Exemple:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## Voir aussi

* Classe [IMathBorderBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)