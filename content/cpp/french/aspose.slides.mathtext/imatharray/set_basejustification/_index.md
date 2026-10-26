---
title: set_BaseJustification()
second_title: Référence API Aspose.Slides pour C++
description: "Spécifie l'alignement du tableau par rapport au texte environnant. Le texte extérieur au tableau peut être aligné avec le bas, le haut ou le centre d'un objet tableau. Valeur par défaut : Center"
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) méthode

Spécifie l'alignement du tableau par rapport au texte environnant. Le texte extérieur au tableau peut être aligné avec le bas, le haut ou le centre d'un objet tableau. Valeur par défaut : Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## Remarques

Exemple :
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Voir aussi

* Énum [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [IMathArray](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)