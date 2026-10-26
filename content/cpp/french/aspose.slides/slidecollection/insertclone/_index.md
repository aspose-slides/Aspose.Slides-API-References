---
title: InsertClone()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection.
type: docs
weight: 66
url: /fr/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) méthode

Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index de la nouvelle diapositive. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) à cloner. |

### Valeur de retour

Diapositive insérée.

## Remarques

Lors du clonage d'une diapositive entre différentes présentations, le maître de la diapositive peut également être cloné. Un registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d'éviter la création de plusieurs clones du même maître de diapositive. Le clonage manuel des maîtres de diapositives ne sera ni empêché ni enregistré. Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) ou [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) pour cloner les diapositives et [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) pour cloner les maîtres. 

L'exemple suivant montre comment cloner à une autre position dans [Presentation](../../presentation/). 
```cpp
// Instanciez la classe Presentation qui représente un fichier de présentation
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Clonez la diapositive souhaitée à la fin de la collection de diapositives dans la même présentation
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Clonez la diapositive souhaitée à l'index spécifié dans la même présentation
slides->InsertClone(2, slides->idx_get(1));
// Enregistrez la présentation modifiée sur le disque
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
 L'exemple suivant montre comment cloner à une autre position dans [Presentation](../../presentation/). 
```cpp
// Instanciez la classe Presentation pour charger le fichier de présentation source
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Instanciez la classe Presentation pour le PPTX de destination (où la diapositive doit être clonée)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Enregistrez la présentation de destination sur le disque
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) méthode

Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index de la nouvelle diapositive. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) à cloner. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Diapositive de mise en page pour une nouvelle diapositive. |

### Valeur de retour

Diapositive insérée.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) méthode

Insère une copie d'une diapositive source spécifiée à la position spécifiée de la collection. La mise en page appropriée sera sélectionnée automatiquement à partir du maître spécifié (une mise en page appropriée est la mise en page ayant le même Type ou le même Nom que la mise en page de la diapositive source). S'il n'y a pas de mise en page appropriée, la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est true) ou une PptxEditException sera levée (si allowCloneMissingLayout est false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index de la nouvelle diapositive. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) à cloner. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositive maître pour une nouvelle diapositive. |
| allowCloneMissingLayout | **bool** | S'il n'y a pas de mise en page appropriée dans le maître spécifié, la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est true) ou une PptxEditException sera levée (si allowCloneMissingLayout est false). |

### Valeur de retour

Diapositive insérée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [SlideCollection](../)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IMasterSlide](../../imasterslide/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)