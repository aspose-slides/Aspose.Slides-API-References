---
title: Insert()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insère une nouvelle diapositive de mise en page à la position spécifiée de la collection.
type: docs
weight: 40
url: /fr/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) méthode


Insère une nouvelle diapositive de mise en page à la position spécifiée de la collection.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indice de la nouvelle diapositive. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Type de mise en page pour une nouvelle mise en page. Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Les autres types de mise en page ne sont pas pris en charge pour le moment : Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée. Si le paramètre null est passé, le nom sera généré automatiquement en fonction du type de mise en page fourni (par exemple \"Title Slide\" ou \"1_Title Slide\", \"2_..\", etc.). |

### Valeur de retour

Diapositive insérée.
## Remarques



La mise en page insérée pour la valeur [SlideLayoutType::Custom](../../slidelayouttype/) de *layoutType* ne contient aucun espace réservé et aucune forme. 

## Voir aussi

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)