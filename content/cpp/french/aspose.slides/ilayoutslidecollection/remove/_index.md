---
title: Remove()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime une mise en page de la collection.
type: docs
weight: 27
url: /fr/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) méthode

Supprime une diapositive de mise en page de la collection.

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | La diapositive de mise en page à supprimer de la collection. |
## Remarques

1) Pour éviter le lancement de l'exception PptxEditException, vérifiez d'abord la propriété HasDependingSlides de la disposition. 2) Vous pouvez également utiliser la méthode [ILayoutSlide::Remove](../../ilayoutslide/remove/) pour simplifier le code. 
## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [ILayoutSlideCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)