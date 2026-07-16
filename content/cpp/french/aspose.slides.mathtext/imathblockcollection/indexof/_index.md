---
title: IndexOf()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine l'indice d'un IMathBlock spécifique dans la collection.
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) méthode

Détermine l'indice d'un [IMathBlock](../../imathblock/) spécifique dans la collection.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | L'élément à rechercher dans la collection. |

### Valeur de retour

L'indice de *item* s'il est trouvé dans la collection ; sinon, -1.

## Remarques



Exemple : 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathBlockCollection](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)