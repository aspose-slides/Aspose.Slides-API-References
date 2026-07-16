---
title: Remove()
second_title: Référence API Aspose.Slides pour C++
description: Supprime une mise en page de la collection.
type: docs
weight: 66
url: /fr/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) méthode


Supprime une mise en page de la collection.

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | La diapositive de mise en page à supprimer de la collection. |
## Remarques



1) Pour éviter le lancement de l'exception PptxEditException, vérifiez la propriété HasDependingSlides du layout au préalable. 2) Vous pouvez également utiliser la méthode [ILayoutSlide::Remove](../../ilayoutslide/remove/) pour simplifier le code. 
## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [LayoutSlideCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)