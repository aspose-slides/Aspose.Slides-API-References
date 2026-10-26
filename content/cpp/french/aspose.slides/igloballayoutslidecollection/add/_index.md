---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une nouvelle diapositive de mise en page à la présentation.
type: docs
weight: 14
url: /fr/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) méthode

Ajoute une nouvelle diapositive de mise en page à la présentation.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositive maîtresse pour une nouvelle mise en page. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Type de mise en page pour une nouvelle mise en page. Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. D'autres types de mise en page ne sont pas pris en charge actuellement : Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée. Si le paramètre null est passé, alors le nom sera généré automatiquement en fonction du type de mise en page fourni (par exemple "Title Slide" ou "1_Title Slide", "2_..", etc.). |

### Valeur de retour

Diapositive ajoutée.

## Remarques

1) La mise en page ajoutée pour la valeur [SlideLayoutType::Custom](../../slidelayouttype/) de *layoutType* ne contient aucun espace réservé et aucune forme. 2) L'analogue de cette méthode est la méthode [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) accessible via la propriété [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Voir aussi

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Class [String](../../../system/string/)
* Class [IGlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)