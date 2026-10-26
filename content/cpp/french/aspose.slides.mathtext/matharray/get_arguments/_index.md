---
title: get_Arguments()
second_title: Référence API Aspose.Slides pour C++
description: Ensemble des éléments du tableau
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() méthode


L'ensemble des éléments du tableau

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
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
* Classe [MathArray](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)