---
title: InsertClone()
second_title: Référence API Aspose.Slides pour C++
description: Insère une copie d'une diapositive maître spécifiée à la position indiquée de la collection. Les diapositives de disposition liées seront également copiées.
type: docs
weight: 105
url: /fr/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) méthode


Insère une copie d’une diapositive maître spécifiée à la position indiquée de la collection. Les diapositives de disposition liées seront également copiées.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index de la nouvelle diapositive. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) à cloner. |

### Valeur de retour

Diapositive maître insérée.

## Remarques



L'exemple suivant montre comment cloner une diapositive maître dans un autre PowerPoint [Presentation](../../presentation/). 
```cpp
// Instancie la classe Presentation pour charger le fichier de présentation source
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Instancie la classe Presentation pour la présentation de destination (où la diapositive sera clonée)
auto destPres = System::MakeObject<Presentation>();

// Instancie ISlide à partir de la collection de diapositives de la présentation source ainsi que
// Diapositive maîtresse
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Obtient les diapositives maîtresses de la présentation de destination
auto masters = destPres->get_Masters();
// Clone la diapositive maîtresse désirée de la présentation source vers la collection des maîtres dans le
// Présentation de destination
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Collection de diapositives dans la présentation de destination
auto slides = destPres->get_Slides();
// Clone la diapositive source dans la collection de diapositives de destination.
slides->AddClone(sourceSlide, iSlide, true);
// Enregistre la présentation de destination sur le disque
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMasterSlide](../../imasterslide/)
* Classe [MasterSlideCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)