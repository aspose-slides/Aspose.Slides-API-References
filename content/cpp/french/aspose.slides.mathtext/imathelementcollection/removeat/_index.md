---
title: RemoveAt()
second_title: Référence API Aspose.Slides pour C++
description: Supprime l'élément à l'index spécifié de la collection.
type: docs
weight: 105
url: /fr/aspose.slides.mathtext/imathelementcollection/removeat/
---
## IMathElementCollection::RemoveAt(int32_t) méthode


Supprime l'élément à l'index spécifié de la collection.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::RemoveAt(int32_t index)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index basé sur zéro de l'élément à supprimer. |
## Remarques



Exemple : 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->RemoveAt(2);
```

## Voir aussi

* Classe [IMathElementCollection](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)