---
title: Clear()
second_title: "Référence de l'API Aspose.Slides pour C++"
description: Supprime tous les éléments de la collection.
type: docs
weight: 118
url: /fr/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() méthode


Supprime tous les éléments de la collection.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Remarques


Exemple: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Voir aussi

* Classe [IMathBlockCollection](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)