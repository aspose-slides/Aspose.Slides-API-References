---
title: ShapeElement class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapeelement/
---
## ShapeElement klass

Representerar en del av en form med samma kontur- och fyllningsegenskaper.

Typen ShapeElement exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`parent_shape`](/slides/python-net/sv/aspose.slides/shapeelement/parent_shape/) | Returnerar en Shape_PPT som elementet skapades för.<br/>            Skrivskyddad [`Shape`](/slides/python-net/sv/aspose.slides/shape). |
| [`path_points`](/slides/python-net/sv/aspose.slides/shapeelement/path_points/) | Hämtar en array av punkter som definierar geometrin för elementets bana. |
| [`path_types`](/slides/python-net/sv/aspose.slides/shapeelement/path_types/) | Hämtar en array av bytevärden som specificerar typen för varje punkt i elementets bana. <br/>            <br/>**0**  Anger att punkten är början på en figur.<br/><br/><br/>**1**  Anger att punkten är en av de två ändpunkterna på en linje.<br/><br/><br/>**3**  Anger att punkten är en ändpunkt eller kontrollpunkt för en kubisk Bezier-spline.<br/><br/><br/>**7**  Maskerar alla bitar utom de tre lägst betydande bitarna, som anger punkttypen.<br/><br/><br/>**16**  Anger att motsvarande segment är streckat.<br/><br/><br/>**32**  Anger att punkten är en markör.<br/><br/><br/>**128**  Anger att punkten är den sista punkten i en sluten delbana (figur).<br/><br/><br/>**129**  Anger en datapunkt som både är en linjesegmentändpunkt och den sista punkten i en sluten delbana. |
| [`fill_source`](/slides/python-net/sv/aspose.slides/shapeelement/fill_source/) | Returnerar information om hur ett element ska fyllas.<br/>            Skrivskyddad [`ShapeElementFillSource`](/slides/python-net/sv/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/sv/aspose.slides/shapeelement/stroke_source/) | Returnerar information om hur ett element ska kontureras.<br/>            Skrivskyddad [`ShapeElementStrokeSource`](/slides/python-net/sv/aspose.slides/shapeelementstrokesource). |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)