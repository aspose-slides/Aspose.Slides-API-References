---
title: Remove()
second_title: Aspose.Slides pour C++ – Référence de l'API
description: Supprime la première occurrence d'un objet spécifique de la collection.
type: docs
weight: 92
url: /fr/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) méthode


Supprime la première occurrence d'un objet spécifique de la collection.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'objet à supprimer de la collection. |

### Valeur de retour

true si *item* a été supprimé avec succès de la collection ; sinon, false. Cette méthode renvoie également false si *item* n'est pas trouvé dans la collection d'origine.

## Remarques



Exemple :
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathElementCollection](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)