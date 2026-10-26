---
title: GeometryPath class
second_title: Aspose.Slides Python számára .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/geometrypath/
---
## GeometryPath osztály

A GeometryShape geometriai útvonalát reprezentálja

A GeometryPath típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides/geometrypath/__init__/#) | Létrehozza a GeometryPath példányát |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`path_data`](/slides/python-net/hu/aspose.slides/geometrypath/path_data/) | Visszaadja a GeometryShape geometriai útvonalát útvonal-szegmensek tömbjeként. |
| [`fill_mode`](/slides/python-net/hu/aspose.slides/geometrypath/fill_mode/) | Beállítja a kitöltési módot |
| [`stroke`](/slides/python-net/hu/aspose.slides/geometrypath/stroke/) | Beállítja a körvonal megjelenését |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/hu/aspose.slides/geometrypath/line_to/#asposeslidespointf) | Vonalat ad az útvonal végéhez |
| [`line_to(self, x, y)`](/slides/python-net/hu/aspose.slides/geometrypath/line_to/#float-float) | Vonalat ad az útvonal végéhez |
| [`line_to(self, point, index)`](/slides/python-net/hu/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | Vonalat ad az útvonal megadott helyére |
| [`line_to(self, x, y, index)`](/slides/python-net/hu/aspose.slides/geometrypath/line_to/#float-float-int) | Vonalat ad az útvonal megadott helyére |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/hu/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Kúbikus Bézier-görbét ad az útvonal végéhez |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/hu/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Kúbikus Bézier-görbét ad az útvonal végéhez |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/hu/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Kúbikus Bézier-görbét ad az útvonal megadott helyére |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/hu/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Kúbikus Bézier-görbét ad az útvonal megadott helyére |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/hu/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Kvadratikus Bézier-görbét ad az útvonal végéhez |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/hu/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Kvadratikus Bézier-görbét ad az útvonal végéhez |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/hu/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Kvadratikus Bézier-görbét ad az útvonal megadott helyére |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/hu/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Kvadratikus Bézier-görbét ad az útvonal megadott helyére |
| [`move_to(self, point)`](/slides/python-net/hu/aspose.slides/geometrypath/move_to/#asposeslidespointf) | Beállítja a következő pont pozícióját. |
| [`move_to(self, x, y)`](/slides/python-net/hu/aspose.slides/geometrypath/move_to/#float-float) | Beállítja a következő pont pozícióját. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/geometrypath/remove_at/#int) | Eltávolítja a szegmenst a geometriai útvonal megadott indexén. |
| [`close_figure(self)`](/slides/python-net/hu/aspose.slides/geometrypath/close_figure/#) | Lezárja a jelenlegi alakzatot ezen az útvonalon |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/hu/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Hozzáfűzi a megadott ívet az útvonalhoz. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)