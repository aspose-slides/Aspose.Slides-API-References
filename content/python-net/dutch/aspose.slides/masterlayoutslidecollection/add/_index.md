---
title: add method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Voegt een nieuwe lay-outdia toe aan het einde van de collectie.

### Retourwaarde

Toegevoegde dia.

```python
def add(self, layout_type, layout_name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/nl/aspose.slides/slidelayouttype) | Indelingstype voor een nieuwe lay-out.<br/><br/>            Ondersteunde indelingstypen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Andere indelingstypen worden momenteel niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid.<br/><br/>            Als de parameter None wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven indelingstype <br/><br/>            (bijvoorbeeld "Title Slide" of "1_Title Slide", "2_..", enz.). |

### Opmerkingen

1) Toegevoegde lay-out voor de waarde SlideLayoutType.Custom van `layout_type` bevat geen tijdelijke aanduidingen en geen vormen.  
2) Analoge van deze methode is methode **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** toegankelijk via de eigenschap [`IPresentation.layout_slides`](/slides/python-net/nl/aspose.slides/ipresentation/layout_slides).

### Uitzonderingen

| Exceptie | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Wordt gegooid als een niet-ondersteunde waarde van parameter `layout_type` wordt doorgegeven. Indelingstypen die momenteel niet worden ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als de lay-outnaam `layout_name` al in gebruik is in <br/>            deze collectie van de lay-outs. |

### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`MasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection)
* enumeratie [`SlideLayoutType`](/slides/python-net/nl/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)