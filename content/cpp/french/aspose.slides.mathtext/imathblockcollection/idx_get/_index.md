---
title: idx_get()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère l'élément à l'index spécifié. IMathBlock en lecture seule.
type: docs
weight: 92
url: /fr/aspose.slides.mathtext/imathblockcollection/idx_get/
---
## IMathBlockCollection::idx_get(int32_t) méthode

Récupère l'élément à l'index spécifié. Lecture seule [IMathBlock](../../imathblock/).

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockCollection::idx_get(int32_t index)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index basé sur zéro de l'élément à obtenir |

### Valeur de retour

Le bloc d'un texte mathématique.

## Remarques



Exemple :
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathBlockCollection](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)