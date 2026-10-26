---
title: get_BaseJustification()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Spécifie l'alignement du tableau par rapport au texte environnant. Le texte à l'extérieur du tableau peut être aligné avec le bas, le haut ou le centre d'un objet tableau. Valeur par défaut: Center"
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() méthode

Spécifie l'alignement du tableau par rapport au texte environnant Le texte à l'extérieur du tableau peut être aligné avec le bas, le haut ou le centre d'un objet tableau. Valeur par défaut: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## Remarques

Exemple: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Voir aussi

* Énum [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [MathArray](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)