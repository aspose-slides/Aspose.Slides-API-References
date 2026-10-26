---
title: RemoveAt()
second_title: Référence API Aspose.Slides pour C++
description: Supprime l'élément à l'index spécifié de la collection.
type: docs
weight: 53
url: /fr/aspose.slides/imasterlayoutslidecollection/removeat/
---
## IMasterLayoutSlideCollection::RemoveAt(int32_t) méthode


Supprime l'élément à l'indice spécifié de la collection.

```cpp
virtual void Aspose::Slides::IMasterLayoutSlideCollection::RemoveAt(int32_t index)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice basé sur zéro de l'élément à supprimer. |
## Remarques



1) Pour éviter le déclenchement de l'exception PptxEditException, vérifiez la propriété HasDependingSlides du layout au préalable. 2) Vous pouvez également utiliser la méthode [ILayoutSlide::Remove](../../ilayoutslide/remove/) pour simplifier le code. 
## Voir aussi

* Classe [IMasterLayoutSlideCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)