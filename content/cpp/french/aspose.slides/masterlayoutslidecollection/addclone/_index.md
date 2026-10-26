---
title: AddClone()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une copie d'une diapositive de mise en page spécifiée à la fin de la collection.
type: docs
weight: 1
url: /fr/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) méthode

Ajoute une copie d'une diapositive de mise en page spécifiée à la fin de la collection.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) à cloner. |

### Valeur de retour

Diapositive ajoutée.

## Remarques

1) La nouvelle mise en page sera liée à la diapositive maître parente pour cette collection de diapositives de mise en page. Il s'agit donc d'un analogue de copier/coller avec l'option \"Use Destination Theme\" dans PowerPoint. 2) Un analogue de cette méthode est la méthode [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) accessible via la propriété [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [MasterLayoutSlideCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)