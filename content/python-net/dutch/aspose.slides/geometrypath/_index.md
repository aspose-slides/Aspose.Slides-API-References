---
title: GeometryPath class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/geometrypath/
---
## GeometryPath klasse

Stelt het geometriepad van GeometryShape voor

Het GeometryPath type biedt de volgende leden:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides/geometrypath/__init__/#) | Maakt een instantie van GeometryPath |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`path_data`](/slides/python-net/nl/aspose.slides/geometrypath/path_data/) | Retourneert het geometriepad van GeometryShape als een array van padsegmenten. |
| [`fill_mode`](/slides/python-net/nl/aspose.slides/geometrypath/fill_mode/) | Stelt opvulmodus in |
| [`stroke`](/slides/python-net/nl/aspose.slides/geometrypath/stroke/) | Stelt de lijnweergave in |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/nl/aspose.slides/geometrypath/line_to/#asposeslidespointf) | Voegt een lijn toe aan het einde van het pad |
| [`line_to(self, x, y)`](/slides/python-net/nl/aspose.slides/geometrypath/line_to/#float-float) | Voegt een lijn toe aan het einde van het pad |
| [`line_to(self, point, index)`](/slides/python-net/nl/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | Voegt een lijn toe op de opgegeven plaats van het pad |
| [`line_to(self, x, y, index)`](/slides/python-net/nl/aspose.slides/geometrypath/line_to/#float-float-int) | Voegt een lijn toe op de opgegeven plaats van het pad |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/nl/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Voegt een kubieke Bézier-curve toe aan het einde van het pad |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/nl/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Voegt een kubieke Bézier-curve toe aan het einde van het pad |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/nl/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Voegt een kubieke Bézier-curve toe op de opgegeven plaats van het pad |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/nl/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Voegt een kubieke Bézier-curve toe op de opgegeven plaats van het pad |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/nl/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Voegt een kwadratische Bézier-curve toe aan het einde van het pad |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/nl/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Voegt een kwadratische Bézier-curve toe aan het einde van het pad |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/nl/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Voegt een kwadratische Bézier-curve toe op de opgegeven plaats van het pad |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/nl/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Voegt een kwadratische Bézier-curve toe op de opgegeven plaats van het pad |
| [`move_to(self, point)`](/slides/python-net/nl/aspose.slides/geometrypath/move_to/#asposeslidespointf) | Stelt de volgende puntpositie in. |
| [`move_to(self, x, y)`](/slides/python-net/nl/aspose.slides/geometrypath/move_to/#float-float) | Stelt de volgende puntpositie in. |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides/geometrypath/remove_at/#int) | Verwijdert segment op de opgegeven index van het geometriepad. |
| [`close_figure(self)`](/slides/python-net/nl/aspose.slides/geometrypath/close_figure/#) | Sluit de huidige figuur van dit pad |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/nl/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Voegt de opgegeven boog toe aan het pad. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)