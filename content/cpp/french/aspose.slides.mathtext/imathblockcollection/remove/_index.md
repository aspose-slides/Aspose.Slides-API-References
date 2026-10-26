---
title: Remove()
second_title: Référence API Aspose.Slides pour C++
description: Supprime la première occurrence d'un objet spécifique de la collection/>
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) méthode


Supprime la première occurrence d'un objet spécifique de la collection/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | L'objet à supprimer de la collection. |

### Valeur de retour

true si *item* a été supprimé avec succès de la collection ; sinon, false. Cette méthode renvoie également false si *item* n'est pas trouvé dans la collection originale/>.

## Remarques



Exemple : 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathBlockCollection](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)