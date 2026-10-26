---
title: IGeometryPath class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/igeometrypath/
---
## IGeometryPath klass

Representerar geometrisk bana för GeometryShape

Typen IGeometryPath exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`path_data`](/slides/python-net/sv/aspose.slides/igeometrypath/path_data/) | Returnerar geometrisk bana för GeometryShape som en array av bansegment. |
| [`fill_mode`](/slides/python-net/sv/aspose.slides/igeometrypath/fill_mode/) | Ställer in fyllningsläge |
| [`stroke`](/slides/python-net/sv/aspose.slides/igeometrypath/stroke/) | Ställer in strekningsutseende |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/sv/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | Lägger till en linje i slutet av banan |
| [`line_to(self, x, y)`](/slides/python-net/sv/aspose.slides/igeometrypath/line_to/#float-float) | Lägger till en linje i slutet av banan |
| [`line_to(self, point, index)`](/slides/python-net/sv/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | Lägger till en linje på den angivna platsen i banan |
| [`line_to(self, x, y, index)`](/slides/python-net/sv/aspose.slides/igeometrypath/line_to/#float-float-int) | Lägger till en linje på den angivna platsen i banan |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/sv/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Lägger till en kubisk Bézierkurva i slutet av banan |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/sv/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Lägger till en kubisk Bézierkurva i slutet av banan |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/sv/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Lägger till en kubisk Bézierkurva på den angivna platsen i banan |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/sv/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Lägger till en kubisk Bézierkurva på den angivna platsen i banan |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/sv/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Lägger till en kvadratisk Bézierkurva i slutet av banan |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/sv/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Lägger till en kvadratisk Bézierkurva i slutet av banan |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/sv/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Lägger till en kvadratisk Bézierkurva på den angivna platsen i banan |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/sv/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Lägger till en kvadratisk Bézierkurva på den angivna platsen i banan |
| [`move_to(self, point)`](/slides/python-net/sv/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | Ställer in nästa punktposition. |
| [`move_to(self, x, y)`](/slides/python-net/sv/aspose.slides/igeometrypath/move_to/#float-float) | Ställer in nästa punktposition. |
| [`remove_at(self, index)`](/slides/python-net/sv/aspose.slides/igeometrypath/remove_at/#int) | Tar bort segmentet på det angivna indexet i geometribanan. |
| [`close_figure(self)`](/slides/python-net/sv/aspose.slides/igeometrypath/close_figure/#) | Stänger den aktuella figuren i denna bana |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/sv/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Lägger till den angivna bågen till banan. |

### Se också
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)