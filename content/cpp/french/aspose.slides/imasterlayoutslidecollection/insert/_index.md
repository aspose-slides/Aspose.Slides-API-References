---
title: Insert()
second_title: Référence API Aspose.Slides pour C++
description: Insère une nouvelle diapositive de mise en page à la position spécifiée de la collection.
type: docs
weight: 40
url: /fr/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) méthode

Insère une nouvelle diapositive de mise en page à la position spécifiée de la collection.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indice de la nouvelle diapositive. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Type de mise en page pour une nouvelle mise en page. Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Les autres types de mise en page ne sont pas pris en charge actuellement : Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée. Si le paramètre null est passé, le nom est généré automatiquement en fonction du type de mise en page fourni (par exemple "Title Slide" ou "1_Title Slide", "2_..", etc.). |

### Valeur de retour

Diapositive insérée.

## Remarques

La mise en page insérée pour la valeur [SlideLayoutType::Custom](../../slidelayouttype/) de *layoutType* ne contient aucun espace réservé ni aucune forme. 

## Voir aussi

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)