---
title: IGeometryPath class
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/igeometrypath/
---
## IGeometryPath osztály

Represents geometry path of GeometryShape

The IGeometryPath type exposes the following members:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`path_data`](/slides/python-net/hu/aspose.slides/igeometrypath/path_data/) | Visszaadja a GeometryShape geometriai útvonalát útvonal szegmensek tömbjeként. |
| [`fill_mode`](/slides/python-net/hu/aspose.slides/igeometrypath/fill_mode/) | Beállítja a kitöltési módot |
| [`stroke`](/slides/python-net/hu/aspose.slides/igeometrypath/stroke/) | Beállítja a vonal megjelenését |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/hu/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | Hozzáad egy vonalat az útvonal végéhez |
| [`line_to(self, x, y)`](/slides/python-net/hu/aspose.slides/igeometrypath/line_to/#float-float) | Hozzáad egy vonalat az útvonal végéhez |
| [`line_to(self, point, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | Hozzáad egy vonalat az útvonal megadott helyéhez |
| [`line_to(self, x, y, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/line_to/#float-float-int) | Hozzáad egy vonalat az útvonal megadott helyéhez |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/hu/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Hozzáad egy köbös Bézier-görbét az útvonal végéhez |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/hu/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Hozzáad egy köbös Bézier-görbét az útvonal végéhez |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Hozzáad egy köbös Bézier-görbét az útvonal megadott helyéhez |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Hozzáad egy köbös Bézier-görbét az útvonal megadott helyéhez |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/hu/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Hozzáad egy kvadratikus Bézier-görbét az útvonal végéhez |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/hu/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Hozzáad egy kvadratikus Bézier-görbét az útvonal végéhez |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Hozzáad egy kvadratikus Bézier-görbét az útvonal megadott helyéhez |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Hozzáad egy kvadratikus Bézier-görbét az útvonal megadott helyéhez |
| [`move_to(self, point)`](/slides/python-net/hu/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | Beállítja a következő pont pozícióját. |
| [`move_to(self, x, y)`](/slides/python-net/hu/aspose.slides/igeometrypath/move_to/#float-float) | Beállítja a következő pont pozícióját. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/remove_at/#int) | Eltávolítja az útvonal szegmensét a megadott indexnél a geometriai útvonalból. |
| [`close_figure(self)`](/slides/python-net/hu/aspose.slides/igeometrypath/close_figure/#) | Lezárja az aktuális alakzatot ezen az útvonalon |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/hu/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Hozzáfűzi a megadott ívet az útvonalhoz. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)