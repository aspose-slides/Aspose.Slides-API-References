---
title: set_BaseJustification()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Spécifie l'alignement du tableau par rapport au texte environnant. Le texte situé à l'extérieur du tableau peut être aligné avec le bas, le haut ou le centre d'un objet tableau. Valeur par défaut : Center"
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) méthode

Spécifie l'alignement du tableau par rapport au texte environnant. Le texte extérieur au tableau peut être aligné avec le bas, le haut ou le centre d'un objet tableau. Valeur par défaut : Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## Remarques

Exemple :
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Voir aussi

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [MathArray](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)