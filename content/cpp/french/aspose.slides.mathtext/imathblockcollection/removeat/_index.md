---
title: RemoveAt()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime un élément à l'indice spécifié de la collection.
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) méthode


Supprime un élément à l'indice spécifié de la collection.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice basé sur zéro de l'élément à supprimer. |
## Remarques



Exemple : 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## Voir aussi

* Classe [IMathBlockCollection](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)