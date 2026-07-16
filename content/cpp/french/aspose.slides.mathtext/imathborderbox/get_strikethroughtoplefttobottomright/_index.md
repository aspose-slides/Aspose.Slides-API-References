---
title: get_StrikethroughTopLeftToBottomRight()
second_title: Référence de l'API Aspose.Slides pour C++
description: Biffure du coin supérieur gauche au coin inférieur droit (par défaut false). Spécifie l'état masqué ou affiché d'une ligne diagonale de biffure du coin supérieur gauche au coin inférieur droit de la boîte de bordure.
type: docs
weight: 196
url: /fr/aspose.slides.mathtext/imathborderbox/get_strikethroughtoplefttobottomright/
---
## IMathBorderBox::get_StrikethroughTopLeftToBottomRight() method


Biffure du coin supérieur gauche au coin inférieur droit (default is false). Spécifie l'état masqué ou affiché d'une ligne diagonale de biffure du coin supérieur gauche au coin inférieur droit de la boîte de bordure.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughTopLeftToBottomRight()=0
```

## Remarques


Exemple: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughTopLeftToBottomRight(true);
```

## Voir aussi

* Classe [IMathBorderBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)