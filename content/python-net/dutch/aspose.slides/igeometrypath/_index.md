---
title: IGeometryPath class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/igeometrypath/
---
## IGeometryPath klasse

Stelt het geometriepAd van GeometryShape voor

Het IGeometryPath-type bevat de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`path_data`](/slides/python-net/nl/aspose.slides/igeometrypath/path_data/) | Retourneert het geometriepAd van GeometryShape als een array van padsegmenten. |
| [`fill_mode`](/slides/python-net/nl/aspose.slides/igeometrypath/fill_mode/) | Stelt de vullingsmodus in. |
| [`stroke`](/slides/python-net/nl/aspose.slides/igeometrypath/stroke/) | Stelt de lijnopmaak in. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/nl/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | Voegt een lijn toe aan het einde van het pad |
| [`line_to(self, x, y)`](/slides/python-net/nl/aspose.slides/igeometrypath/line_to/#float-float) | Voegt een lijn toe aan het einde van het pad |
| [`line_to(self, point, index)`](/slides/python-net/nl/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | Voegt een lijn toe op de opgegeven plaats van het pad |
| [`line_to(self, x, y, index)`](/slides/python-net/nl/aspose.slides/igeometrypath/line_to/#float-float-int) | Voegt een lijn toe op de opgegeven plaats van het pad |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/nl/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Voegt een kubieke Bézier-curve toe aan het einde van het pad |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/nl/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Voegt een kubieke Bézier-curve toe aan het einde van het pad |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/nl/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Voegt een kubieke Bézier-curve toe op de opgegeven plaats van het pad |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/nl/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Voegt een kubieke Bézier-curve toe op de opgegeven plaats van het pad |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/nl/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Voegt een kwadratische Bézier-curve toe aan het einde van het pad |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/nl/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Voegt een kwadratische Bézier-curve toe aan het einde van het pad |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/nl/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Voegt een kwadratische Bézier-curve toe op de opgegeven plaats van het pad |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/nl/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Voegt een kwadratische Bézier-curve toe op de opgegeven plaats van het pad |
| [`move_to(self, point)`](/slides/python-net/nl/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | Stelt de positie van het volgende punt in. |
| [`move_to(self, x, y)`](/slides/python-net/nl/aspose.slides/igeometrypath/move_to/#float-float) | Stelt de positie van het volgende punt in. |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides/igeometrypath/remove_at/#int) | Verwijdert het segment op de opgegeven index van het geometriepAd. |
| [`close_figure(self)`](/slides/python-net/nl/aspose.slides/igeometrypath/close_figure/#) | Sluit de huidige figuur van dit pad |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/nl/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Voegt de opgegeven boog toe aan het pad. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)