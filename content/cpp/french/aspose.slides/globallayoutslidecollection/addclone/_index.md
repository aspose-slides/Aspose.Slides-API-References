---
title: AddClone()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une copie d'une diapositive de mise en page spécifiée à la présentation.
type: docs
weight: 1
url: /fr/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) méthode


Ajoute une copie d’une diapositive de mise en page spécifiée à la présentation.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) à cloner. |

### Valeur de retour

Diapositive ajoutée.
## Remarques



Lorsque vous clonez une mise en page entre différentes présentations, le maître de la mise en page peut également être cloné afin de conserver le formatage source. Un registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d’éviter la création de multiples clones du même maître de diapositive. Le clonage manuel des maîtres de diapositives n’est ni empêché ni enregistré. 
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) méthode


Ajoute une copie d’une diapositive de mise en page spécifiée à la présentation.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) à cloner. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositive maîtresse pour une nouvelle mise en page. |

### Valeur de retour

Diapositive ajoutée.
## Remarques



1) La nouvelle mise en page sera liée au maître défini dans la présentation de destination. Ainsi, il s’agit d’une analogie de copier/coller avec l’option « Utiliser le thème de destination » dans PowerPoint. 2) L’analogue de cette méthode est la méthode [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) accessible via la propriété [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/). 
## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [GlobalLayoutSlideCollection](../)
* Classe [IMasterSlide](../../imasterslide/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)