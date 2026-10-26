---
title: GeometryPath class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/geometrypath/
---
## GeometryPath klass

Representerar geometrisk bana för GeometryShape

GeometryPath-typen exponerar följande medlemmar:

## Konstruktörer

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides/geometrypath/__init__/#) | Skapar en instans av GeometryPath |

## Egenskaper

| Property | Description |
| :- | :- |
| [`path_data`](/slides/python-net/sv/aspose.slides/geometrypath/path_data/) | Returnerar geometrisk bana för GeometryShape som en array av bansegment. |
| [`fill_mode`](/slides/python-net/sv/aspose.slides/geometrypath/fill_mode/) | Ställer in fyllningsläge |
| [`stroke`](/slides/python-net/sv/aspose.slides/geometrypath/stroke/) | Ställer in linjens utseende |

## Metoder

| Method | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/sv/aspose.slides/geometrypath/line_to/#asposeslidespointf) | Lägger till en linje i slutet av banan |
| [`line_to(self, x, y)`](/slides/python-net/sv/aspose.slides/geometrypath/line_to/#float-float) | Lägger till en linje i slutet av banan |
| [`line_to(self, point, index)`](/slides/python-net/sv/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | Lägger till en linje på den angivna platsen i banan |
| [`line_to(self, x, y, index)`](/slides/python-net/sv/aspose.slides/geometrypath/line_to/#float-float-int) | Lägger till en linje på den angivna platsen i banan |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/sv/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Lägger till en kubisk Bézier-kurva i slutet av banan |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/sv/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Lägger till en kubisk Bézier-kurva i slutet av banan |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/sv/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Lägger till en kubisk Bézier-kurva på den angivna platsen i banan |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/sv/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Lägger till en kubisk Bézier-kurva på den angivna platsen i banan |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/sv/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Lägger till en kvadratisk Bézier-kurva i slutet av banan |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/sv/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Lägger till en kvadratisk Bézier-kurva i slutet av banan |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/sv/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Lägger till en kvadratisk Bézier-kurva på den angivna platsen i banan |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/sv/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Lägger till en kvadratisk Bézier-kurva på den angivna platsen i banan |
| [`move_to(self, point)`](/slides/python-net/sv/aspose.slides/geometrypath/move_to/#asposeslidespointf) | Ställer in nästa punkts position. |
| [`move_to(self, x, y)`](/slides/python-net/sv/aspose.slides/geometrypath/move_to/#float-float) | Ställer in nästa punkts position. |
| [`remove_at(self, index)`](/slides/python-net/sv/aspose.slides/geometrypath/remove_at/#int) | Tar bort segmentet vid det angivna indexet i geometrisk bana. |
| [`close_figure(self)`](/slides/python-net/sv/aspose.slides/geometrypath/close_figure/#) | Stänger den aktuella figuren i denna bana |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/sv/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Lägger till den angivna bågen i banan. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)