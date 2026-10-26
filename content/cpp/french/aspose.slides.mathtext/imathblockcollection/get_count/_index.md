---
title: get_Count()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int32_t.
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() méthode

Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Remarques

Exemple : 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## Voir aussi

* Classe [IMathBlockCollection](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)