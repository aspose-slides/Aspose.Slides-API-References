---
title: add method
second_title: Aspose.Slides a Python számára .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Új elrendezési diát ad a bemutatóhoz.

### Visszatérési érték

Hozzáadott dia.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide) | Mesterdia egy új elrendezéshez. |
| layout_type | [`SlideLayoutType`](/slides/python-net/hu/aspose.slides/slidelayouttype) | Elrendezéstípus egy új elrendezéshez.<br/><br/>            Támogatott elrendezéstípusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            A többi elrendezéstípus jelenleg nincs támogatva: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException lesz dobva.<br/><br/>            Ha a None paraméter kerül átadásra, a név automatikusan generálódik a megadott elrendezéstípus alapján <br/><br/>            (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

### Megjegyzések

1) A `layout_type` **SlideLayoutType.Custom** értékéhez hozzáadott elrendezés nem tartalmaz helyőrzőket és alakzatokat.
2) Ennek a metódusnak az analógja a **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** metódus, amely a [`IMasterSlide.layout_slides`](/slides/python-net/hu/aspose.slides/imasterslide/layout_slides) tulajdonnal érhető el.

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Dobásra kerül, ha a `layout_type` paraméter nem támogatott értéke kerül átadásra. Jelenleg nem támogatott elrendezéstípusok: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Dobásra kerül, ha a `master` None. |
| **RuntimeError(Proxy error(ArgumentException))** | Dobásra kerül, ha a `master` egy másik bemutatóhoz tartozik. |
| **RuntimeError(Proxy error(ArgumentException))** | Dobásra kerül, ha a `layout_name` elrendezésnév már használatban van a `master` elrendezéseinek gyűjteményében. |



### Lásd még
* osztály [`GlobalLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/globallayoutslidecollection)
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide)
* enumeráció [`SlideLayoutType`](/slides/python-net/hu/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)