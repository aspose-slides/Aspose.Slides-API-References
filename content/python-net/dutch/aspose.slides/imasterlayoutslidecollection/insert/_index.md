---
title: insert method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Voegt een nieuwe layout-dia toe op de opgegeven positie in de collectie.

### Retour

Ingevoegde dia.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Index van de nieuwe dia. |
| layout_type | [`SlideLayoutType`](/slides/python-net/nl/aspose.slides/slidelayouttype) | Layouttype voor een nieuwe layout.<br/><br/> Ondersteunde layouttypes: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/> Andere layouttypes worden momenteel niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Naam voor een nieuwe layout. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid.<br/><br/> Als de parameter None wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven layouttype <br/><br/> (bijvoorbeeld "Title Slide" of "1_Title Slide", "2_..", enz.). |

### Opmerkingen

Ingevoegde layout voor de waarde SlideLayoutType.Custom van `layout_type` bevat geen plaatshouders en geen vormen.

### Excepties

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Wordt gegooid als een niet-ondersteunde waarde van parameter `layout_type` wordt doorgegeven. Layout-types die momenteel niet worden ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als de layouternaam `layout_name` al in gebruik is in deze collectie van layouts. |



### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`IMasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/imasterlayoutslidecollection)
* enumeratie [`SlideLayoutType`](/slides/python-net/nl/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)