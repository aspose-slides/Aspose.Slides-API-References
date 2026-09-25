---
title: IGeometryPath class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/igeometrypath/
---
## třída IGeometryPath

Reprezentuje geometrickou cestu objektu GeometryShape

Typ IGeometryPath vystavuje následující členy:

## Vlastnosti

| Property | Popis |
| :- | :- |
| [`path_data`](/slides/python-net/cs/aspose.slides/igeometrypath/path_data/) | Vrací geometrickou cestu objektu GeometryShape jako pole segmentů cesty. |
| [`fill_mode`](/slides/python-net/cs/aspose.slides/igeometrypath/fill_mode/) | Nastavuje režim výplně |
| [`stroke`](/slides/python-net/cs/aspose.slides/igeometrypath/stroke/) | Nastavuje vzhled tahu |

## Metody

| Method | Popis |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/cs/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | Přidá čáru na konec cesty |
| [`line_to(self, x, y)`](/slides/python-net/cs/aspose.slides/igeometrypath/line_to/#float-float) | Přidá čáru na konec cesty |
| [`line_to(self, point, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | Přidá čáru na zadané místo cesty |
| [`line_to(self, x, y, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/line_to/#float-float-int) | Přidá čáru na zadané místo cesty |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/cs/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Přidá kubickou Bezierovu křivku na konec cesty |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/cs/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Přidá kubickou Bezierovu křivku na konec cesty |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Přidá kubickou Bezierovu křivku na zadané místo cesty |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Přidá kubickou Bezierovu křivku na zadané místo cesty |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/cs/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Přidá kvadratickou Bezierovu křivku na konec cesty |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/cs/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Přidá kvadratickou Bezierovu křivku na konec cesty |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Přidá kvadratickou Bezierovu křivku na zadané místo cesty |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Přidá kvadratickou Bezierovu křivku na zadané místo cesty |
| [`move_to(self, point)`](/slides/python-net/cs/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | Nastavuje pozici dalšího bodu. |
| [`move_to(self, x, y)`](/slides/python-net/cs/aspose.slides/igeometrypath/move_to/#float-float) | Nastavuje pozici dalšího bodu. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/remove_at/#int) | Odstraní segment na zadaném indexu geometrické cesty. |
| [`close_figure(self)`](/slides/python-net/cs/aspose.slides/igeometrypath/close_figure/#) | Uzavře aktuální útvar této cesty |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/cs/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Přidá zadaný oblouk na cestu. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)