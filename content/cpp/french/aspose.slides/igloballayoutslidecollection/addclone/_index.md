---
title: AddClone()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une copie d'une diapositive de disposition spécifiée à la présentation.
type: docs
weight: 1
url: /fr/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) méthode

Ajoute une copie d’une diapositive de disposition spécifiée à la présentation.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) à cloner. |

### Valeur de retour

Diapositive ajoutée.

## Remarques

Lors du clonage d’une disposition entre différentes présentations, le maître de la disposition peut également être cloné afin de conserver le formatage source. Un registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d’empêcher la création de plusieurs clones du même diapositive maître. Le clonage manuel des diapositives maîtresses ne sera ni empêché ni enregistré. 

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) méthode

Ajoute une copie d’une diapositive de disposition spécifiée à la présentation.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) à cloner. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositive maîtresse pour une nouvelle disposition. |

### Valeur de retour

Diapositive ajoutée.

## Remarques

Une nouvelle disposition sera liée au maître défini dans la présentation de destination. C’est donc l’équivalent d’un copier/coller avec l’option « Utiliser le thème de destination » dans PowerPoint. 

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IGlobalLayoutSlideCollection](../)
* Classe [IMasterSlide](../../imasterslide/)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)