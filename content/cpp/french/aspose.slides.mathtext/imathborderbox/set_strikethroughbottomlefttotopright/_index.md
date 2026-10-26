---
title: set_StrikethroughBottomLeftToTopRight()
second_title: Référence API Aspose.Slides for C++
description: Barré du coin inférieur gauche au coin supérieur droit (false par défaut). Spécifie l'état masqué ou affiché d'une ligne diagonale de barré du coin inférieur gauche au coin supérieur droit de la boîte de bordure.
type: docs
weight: 183
url: /fr/aspose.slides.mathtext/imathborderbox/set_strikethroughbottomlefttotopright/
---
## IMathBorderBox::set_StrikethroughBottomLeftToTopRight(bool) méthode


Barre diagonale du coin inférieur gauche au coin supérieur droit (la valeur par défaut est false). Spécifie l'état masqué ou affiché d'une ligne diagonale de barré du coin inférieur gauche au coin supérieur droit de la boîte de bordure.

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughBottomLeftToTopRight(bool value)=0
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