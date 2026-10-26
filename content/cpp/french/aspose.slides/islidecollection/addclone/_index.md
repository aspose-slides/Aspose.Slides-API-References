---
title: AddClone()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une copie d'une diapositive spécifiée à la fin de la collection.
type: docs
weight: 14
url: /fr/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) method

Ajoute une copie d'une diapositive spécifiée à la fin de la collection.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) à cloner. |

### Valeur de retour

Nouvelle diapositive.

## Remarques



Lors du clonage d'une diapositive entre différentes présentations, le maître de la diapositive peut également être cloné. Un registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d'éviter la création de multiples clones du même maître de diapositive. Le clonage manuel des maîtres de diapositives n'est ni empêché ni enregistré. Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) ou [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) pour cloner des diapositives, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) ou [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) pour cloner des dispositions et [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) pour cloner des maîtres. 
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) method

Ajoute une copie d'une diapositive spécifiée à la fin de la section spécifiée.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```

### Paramètres

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

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method

Ajoute une copie d'une diapositive spécifiée à la fin de la collection.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) à cloner. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Disposition de la diapositive pour une nouvelle diapositive. |

### Valeur de retour

Nouvelle diapositive.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method

Ajoute une copie d'une diapositive source spécifiée à la fin de la collection. La disposition appropriée sera sélectionnée automatiquement à partir du maître spécifié (la disposition appropriée est la disposition ayant le même Type ou le même Nom que la disposition de la diapositive source). S'il n'existe aucune disposition appropriée, la disposition de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) à cloner. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Maître de la diapositive pour une nouvelle diapositive. |
| allowCloneMissingLayout | **bool** | Si aucune disposition appropriée n'existe dans le maître spécifié, la disposition de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux). |

### Valeur de retour

Nouvelle diapositive.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Class [ISection](../../isection/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)