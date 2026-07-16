---
title: get_Arguments()
second_title: Référence API Aspose.Slides pour C++
description: Ensemble d'éléments du tableau
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() méthode

Ensemble d'éléments du tableau

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## Remarques

Exemple: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElementCollection](../../imathelementcollection/)
* Classe [IMathArray](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)