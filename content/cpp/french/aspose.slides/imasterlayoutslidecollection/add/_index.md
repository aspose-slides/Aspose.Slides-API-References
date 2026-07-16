---
title: Add()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute une nouvelle diapositive de mise en page à la fin de la collection.
type: docs
weight: 27
url: /fr/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) méthode


Ajoute une nouvelle diapositive de mise en page à la fin de la collection.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Type de mise en page pour une nouvelle mise en page. Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Les autres types de mise en page ne sont pas pris en charge actuellement : Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée. Si un paramètre null est passé, le nom est généré automatiquement en fonction du type de mise en page fourni (par exemple \"Title Slide\" ou \"1_Title Slide\", \"2_..\", etc.). |

### Valeur de retour

Diapositive ajoutée.
## Remarques



1) La mise en page ajoutée pour la valeur [SlideLayoutType::Custom](../../slidelayouttype/) de *layoutType* ne contient aucun espace réservé et aucune forme. 2) L'analogue de cette méthode est la méthode [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) accessible via la propriété [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 

## Voir aussi

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [String](../../../system/string/)
* Classe [IMasterLayoutSlideCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)