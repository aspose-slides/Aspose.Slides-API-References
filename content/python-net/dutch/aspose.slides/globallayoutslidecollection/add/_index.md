---
title: add method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Voegt een nieuwe lay-outdia toe aan de presentatie.

### Retourwaarde

Toegevoegde dia.

```python
def add(self, master, layout_type, layout_name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/nl/aspose.slides/imasterslide) | Hoofddia voor een nieuwe lay-out. |
| layout_type | [`SlideLayoutType`](/slides/python-net/nl/aspose.slides/slidelayouttype) | Lay-outtype voor een nieuwe lay-out.<br/><br/>            Ondersteunde lay-outtypen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Andere lay-outtypen worden momenteel niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid.<br/><br/>            Als de parameter None wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven lay-outtype <br/><br/>            (bijvoorbeeld "Title Slide" of "1_Title Slide", "2_..", enz.). |

### Opmerkingen

1) Toegevoegde lay-out voor waarde SlideLayoutType.Custom van `layout_type` bevat geen tijdelijke aanduidingen en geen vormen.  
2) Analoge van deze methode is methode **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** benaderd via eigenschap [`IMasterSlide.layout_slides`](/slides/python-net/nl/aspose.slides/imasterslide/layout_slides).

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Gegooid als een niet-ondersteunde waarde voor parameter `layout_type` wordt doorgegeven. Lay-outtypen die momenteel niet worden ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Gegooid als `master` None is. |
| **RuntimeError(Proxy error(ArgumentException))** | Gegooid als `master` tot een andere presentatie behoort. |
| **RuntimeError(Proxy error(ArgumentException))** | Gegooid als lay-outnaamwaarde `layout_name` al in gebruik is in <br/>            collectie van de lay-outs van `master`. |

### Zie ook
* klasse [`GlobalLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/globallayoutslidecollection)
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`IMasterSlide`](/slides/python-net/nl/aspose.slides/imasterslide)
* enumeratie [`SlideLayoutType`](/slides/python-net/nl/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)