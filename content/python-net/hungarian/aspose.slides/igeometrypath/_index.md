---
title: IGeometryPath class
second_title: Aspose.Slides a Python .NET API-re vonatkozó hivatkozás
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
| [`stroke`](/slides/python-net/hu/aspose.slides/igeometrypath/stroke/) | Beállítja a körvonal megjelenését |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/hu/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | Vonalat ad a útvonal végéhez |
| [`line_to(self, x, y)`](/slides/python-net/hu/aspose.slides/igeometrypath/line_to/#float-float) | Vonalat ad a útvonal végéhez |
| [`line_to(self, point, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | Vonalat ad az útvonal megadott helyéhez |
| [`line_to(self, x, y, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/line_to/#float-float-int) | Vonalat ad az útvonal megadott helyéhez |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/hu/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Köbös Bézier-görbét ad a útvonal végéhez |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/hu/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Köbös Bézier-görbét ad a útvonal végéhez |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Köbös Bézier-görbét ad az útvonal megadott helyéhez |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Köbös Bézier-görbét ad az útvonal megadott helyéhez |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/hu/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Másodfokú Bézier-görbét ad a útvonal végéhez |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/hu/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Másodfokú Bézier-görbét ad a útvonal végéhez |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Másodfokú Bézier-görbét ad az útvonal megadott helyéhez |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Másodfokú Bézier-görbét ad az útvonal megadott helyéhez |
| [`move_to(self, point)`](/slides/python-net/hu/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | Beállítja a következő pont pozícióját. |
| [`move_to(self, x, y)`](/slides/python-net/hu/aspose.slides/igeometrypath/move_to/#float-float) | Beállítja a következő pont pozícióját. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/igeometrypath/remove_at/#int) | Eltávolít egy szegmenst a geometriai útvonal megadott indexén. |
| [`close_figure(self)`](/slides/python-net/hu/aspose.slides/igeometrypath/close_figure/#) | Lezárja az aktuális alakzatot ezen az útvonalon |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/hu/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Hozzáadja a megadott ívet az útvonalhoz. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)