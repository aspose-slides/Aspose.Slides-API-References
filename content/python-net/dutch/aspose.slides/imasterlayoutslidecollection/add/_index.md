---
title: add method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Voegt een nieuwe layoutdia toe aan het einde van de collectie.

### Retour

Toegevoegde dia.



```python
def add(self, layout_type, layout_name):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/nl/aspose.slides/slidelayouttype) | Layout type for a new layout.<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Naam voor een nieuwe layout. Als de meegegeven naam al in gebruik is, wordt een ArgumentException gegooid.<br/><br/>            Als de parameter None wordt meegegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven layout type <br/><br/>            (bijvoorbeeld "Title Slide" of "1_Title Slide", "2_..", etc.). |

### Opmerkingen

1) Toegevoegde layout voor de waarde SlideLayoutType.Custom van `layout_type` bevat geen placeholders en geen vormen.  
2) Het equivalent van deze methode is methode **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** die wordt benaderd via de eigenschap [`IPresentation.layout_slides`](/slides/python-net/nl/aspose.slides/ipresentation/layout_slides).

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Gegooid als een niet-ondersteunde waarde van parameter `layout_type` wordt meegegeven. Layout types die momenteel niet worden ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Gegooid als de layouternaam `layout_name` al in gebruik is in deze collectie van de layouts. |



### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`IMasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/imasterlayoutslidecollection)
* enumeratie [`SlideLayoutType`](/slides/python-net/nl/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)