---
title: add method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Új elrendezésdiát ad a bemutatóhoz.

### Visszatér

Hozzáadott dia.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide) | Mesterdia egy új elrendezéshez. |
| layout_type | [`SlideLayoutType`](/slides/python-net/hu/aspose.slides/slidelayouttype) | Elrendezés típusa egy új elrendezéshez.<br/><br/>            Támogatott elrendezés típusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            A többi elrendezés típus jelenleg nem támogatott: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException lesz dobva.<br/><br/>            Ha a None paramétert adják meg, akkor a név automatikusan generálódik a megadott elrendezés típusa alapján.<br/><br/>            (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

### Megjegyzés

1) A `layout_type` értékének SlideLayoutType.Custom hozzáadott elrendezés nem tartalmaz helyőrzőket és alakzatokat.  
2) Ennek a metódusnak az analógja a **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** metódus, amely a [`IMasterSlide.layout_slides`](/slides/python-net/hu/aspose.slides/imasterslide/layout_slides) tulajdonnal érhető el.

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Kivétel dobódik, ha a `layout_type` paraméterhez nem támogatott érték van megadva. Jelenleg nem támogatott elrendezés típusok: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Kivétel dobódik, ha a `master` értéke None. |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel dobódik, ha a `master` egy másik bemutatóhoz tartozik. |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel dobódik, ha a `layout_name` érték már használatban van a <br/>`master` elrendezéseinek gyűjteményében. |



### Lásd még
* osztály [`IGlobalLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/igloballayoutslidecollection)
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide)
* enumeráció [`SlideLayoutType`](/slides/python-net/hu/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)