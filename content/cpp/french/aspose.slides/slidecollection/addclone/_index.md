---
title: AddClone()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute une copie d'une diapositive spécifiée à la fin de la collection.
type: docs
weight: 53
url: /fr/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) méthode

Ajoute une copie d’une diapositive spécifiée à la fin de la collection.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) à cloner. |

### Valeur de retour

Nouvelle diapositive.

## Remarques

Lors du clonage d’une diapositive entre différentes présentations, le maître de la diapositive peut également être cloné. Un registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d’éviter la création de plusieurs clones du même maître de diapositive. Le clonage manuel des maîtres de diapositive n’est ni empêché ni enregistré. Si vous avez besoin de davantage de contrôle sur le processus de clonage, utilisez [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) ou [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) pour cloner des diapositives, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) ou [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) pour cloner des dispositions et [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) pour cloner des maîtres.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) méthode

Ajoute une copie d’une diapositive spécifiée à la fin de la section spécifiée.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) à cloner. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) pour une nouvelle diapositive. |

### Valeur de retour

Nouvelle diapositive.

## Remarques

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Maintenant la deuxième section contient une copie de la première diapositive.
```

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) méthode

Ajoute une copie d’une diapositive spécifiée à la fin de la collection.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) à cloner. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Diapositive de disposition pour une nouvelle diapositive. |

### Valeur de retour

Nouvelle diapositive.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) méthode

Ajoute une copie d’une diapositive source spécifiée à la fin de la collection. La disposition appropriée sera sélectionnée automatiquement à partir du maître spécifié (la disposition appropriée est celle ayant le même Type ou le même Name que la disposition de la diapositive source). S’il n’y a pas de disposition appropriée, la disposition de la diapositive source sera clonée (si allowCloneMissingLayout est true) ou PptxEditException sera levée (si allowCloneMissingLayout est false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) à cloner. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositive maîtresse pour une nouvelle diapositive. |
| allowCloneMissingLayout | **bool** | S’il n’y a pas de disposition appropriée dans le maître spécifié, la disposition de la diapositive source sera clonée (si allowCloneMissingLayout est true) ou PptxEditException sera levée (si allowCloneMissingLayout est false). |

### Valeur de retour

Nouvelle diapositive.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [SlideCollection](../)
* Class [ISection](../../isection/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)