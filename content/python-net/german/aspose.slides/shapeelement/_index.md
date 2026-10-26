---
title: ShapeElement class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapeelement/
---
## ShapeElement Klasse

Stellt einen Teil einer Form mit denselben Kontur- und Füll-Eigenschaften dar.

Der Typ ShapeElement stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`parent_shape`](/slides/python-net/de/aspose.slides/shapeelement/parent_shape/) | Gibt ein Shape_PPT zurück, für das das Element erstellt wurde.<br/>            Nur-Lesen [`Shape`](/slides/python-net/de/aspose.slides/shape). |
| [`path_points`](/slides/python-net/de/aspose.slides/shapeelement/path_points/) | Ruft ein Array von Punkten ab, das die Geometrie des Pfads des Elements definiert. |
| [`path_types`](/slides/python-net/de/aspose.slides/shapeelement/path_types/) | Ruft ein Array von Byte-Werten ab, das den Typ jedes Punktes im Pfad des Elements angibt. <br/>            <br/>**0**  Gibt an, dass der Punkt der Beginn einer Figur ist.<br/><br/><br/>**1**  Gibt an, dass der Punkt einer der beiden Endpunkte einer Linie ist.<br/><br/><br/>**3**  Gibt an, dass der Punkt ein Endpunkt oder ein Steuerpunkt einer kubischen Bézier-Kurve ist.<br/><br/><br/>**7**  Maskiert alle Bits außer den drei niederwertigen Bits, die den Punkttyp angeben.<br/><br/><br/>**16**  Gibt an, dass das entsprechende Segment gestrichelt ist.<br/><br/><br/>**32**  Gibt an, dass der Punkt ein Marker ist.<br/><br/><br/>**128**  Gibt an, dass der Punkt der letzte Punkt in einem geschlossenen Unterpfad (Figur) ist.<br/><br/><br/>**129**  Gibt an, dass der Datenpunkt sowohl ein Liniensegment-Endpunkt als auch der letzte Punkt eines geschlossenen Unterpfads ist. |
| [`fill_source`](/slides/python-net/de/aspose.slides/shapeelement/fill_source/) | Gibt Informationen darüber zurück, wie ein Element gefüllt wird.<br/>            Nur-Lesen [`ShapeElementFillSource`](/slides/python-net/de/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/de/aspose.slides/shapeelement/stroke_source/) | Gibt Informationen darüber zurück, wie ein Element konturiert wird.<br/>            Nur-Lesen [`ShapeElementStrokeSource`](/slides/python-net/de/aspose.slides/shapeelementstrokesource). |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)