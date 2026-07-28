---
title: Add()
second_title: Aspose.Slides for C++ API referencia
description: Új elrendezés-diát ad a prezentációhoz.
type: docs
weight: 14
url: /hu/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) method

Új elrendezés-diát ad a prezentációhoz.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Új elrendezéshez használandó master dia. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Új elrendezés típusa. Támogatott elrendezéstípusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Jelenleg nem támogatott elrendezéstípusok: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Új elrendezés neve. Ha a megadott név már használatban van, ArgumentException dobódik. Ha null értéket adunk meg, a név automatikusan generálódik a megadott elrendezéstípusnak megfelelően (például „Title Slide” vagy „1_Title Slide”, „2_..”, stb.). |

### Visszatérési érték

Added slide.

## Megjegyzések

1) A(z) [SlideLayoutType::Custom](../../slidelayouttype/) értékű *layoutType* hozzáadott elrendezés nem tartalmaz helyőrzőket és alakzatokat. 2) Ennek a metódusnak az analógja a [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) metódus, amely a [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) tulajdonságon keresztül érhető el.

## Lásd még

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Class [String](../../../system/string/)
* Class [GlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)