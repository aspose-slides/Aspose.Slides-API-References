---
title: InsertClone()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insère une copie d'une diapositive spécifiée à la position indiquée de la collection.
type: docs
weight: 27
url: /fr/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) méthode


Insère une copie d’une diapositive spécifiée à la position indiquée de la collection.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index de la nouvelle diapositive. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) à cloner. |

### Valeur de retour

Diapositive insérée.

## Remarques



Lors du clonage d’une diapositive entre différentes présentations, le maître de la diapositive peut également être cloné. Un registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d’éviter la création de multiples clones du même maître de diapositive. Le clonage manuel des maîtres de diapositives ne sera ni empêché ni enregistré. Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) ou [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) pour cloner les diapositives et [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) pour cloner les maîtres. 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) méthode


Insère une copie d’une diapositive spécifiée à la position indiquée de la collection.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index de la nouvelle diapositive. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) à cloner. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Diapositive de mise en page pour la nouvelle diapositive. |

### Valeur de retour

Diapositive insérée.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) méthode


Insère une copie d’une diapositive source spécifiée à la position indiquée de la collection. La mise en page appropriée sera sélectionnée automatiquement à partir du maître spécifié (la mise en page appropriée est celle dont le Type ou le Name correspond à la mise en page de la diapositive source). S’il n’existe pas de mise en page appropriée, la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est true) ou une PptxEditException sera levée (si allowCloneMissingLayout est false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index de la nouvelle diapositive. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) à cloner. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositive maître pour la nouvelle diapositive. |
| allowCloneMissingLayout | **bool** | S’il n’existe pas de mise en page appropriée dans le maître spécifié, la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est true) ou une PptxEditException sera levée (si allowCloneMissingLayout est false). |

### Valeur de retour

Diapositive insérée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [ISlideCollection](../)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IMasterSlide](../../imasterslide/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)