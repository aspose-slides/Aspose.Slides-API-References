---
title: insert method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Voegt een nieuwe layoutdia toe op de opgegeven positie van de collectie.

### Retourwaarde

Ingevoegde dia.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Index van nieuwe dia. |
| layout_type | [`SlideLayoutType`](/slides/python-net/nl/aspose.slides/slidelayouttype) | Lay-outtype voor een nieuwe lay-out.<br/><br/>Ondersteunde lay-outtypes: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>Andere lay-outtypes worden momenteel niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid.<br/><br/>Als er een None-parameter wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven lay-outtype<br/><br/>(bijvoorbeeld "Title Slide" of "1_Title Slide", "2_..", enz.). |

### Opmerkingen

De ingevoegde lay-out voor de waarde SlideLayoutType.Custom van `layout_type` bevat geen tijdelijke aanduidingen en geen vormen.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Wordt gegooid als een niet-ondersteunde waarde van parameter `layout_type` wordt doorgegeven. Lay-outtypes die momenteel niet worden ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als de lay-outnaamwaarde `layout_name` al in gebruik is in <br/> deze collectie van de lay-outs. |



### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`MasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection)
* enumeratie [`SlideLayoutType`](/slides/python-net/nl/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)