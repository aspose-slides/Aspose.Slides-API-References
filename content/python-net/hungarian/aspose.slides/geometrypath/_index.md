---
title: GeometryPath class
second_title: Aspose.Slides Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/geometrypath/
---
## GeometryPath osztály

A GeometryShape geometriai útvonalát reprezentálja

A GeometryPath típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides/geometrypath/__init__/#) | Létrehozza a GeometryPath példányt |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`path_data`](/slides/python-net/hu/aspose.slides/geometrypath/path_data/) | Visszaadja a GeometryShape geometriai útvonalát útvonal szegmensek tömbjeként. |
| [`fill_mode`](/slides/python-net/hu/aspose.slides/geometrypath/fill_mode/) | Beállítja a kitöltési módot |
| [`stroke`](/slides/python-net/hu/aspose.slides/geometrypath/stroke/) | Beállítja a vonal megjelenését |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/hu/aspose.slides/geometrypath/line_to/#asposepydrawingpointf) | Hozzáad egy vonalat az útvonal végéhez |
| [`line_to(self, x, y)`](/slides/python-net/hu/aspose.slides/geometrypath/line_to/#float-float) | Hozzáad egy vonalat az útvonal végéhez |
| [`line_to(self, point, index)`](/slides/python-net/hu/aspose.slides/geometrypath/line_to/#asposepydrawingpointf-int) | Hozzáad egy vonalat az útvonal megadott helyéhez |
| [`line_to(self, x, y, index)`](/slides/python-net/hu/aspose.slides/geometrypath/line_to/#float-float-int) | Hozzáad egy vonalat az útvonal megadott helyéhez |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/hu/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Hozzáad egy köbös Bézier-görbét az útvonal végéhez |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/hu/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Hozzáad egy köbös Bézier-görbét az útvonal végéhez |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/hu/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Hozzáad egy köbös Bézier-görbét az útvonal megadott helyéhez |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/hu/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Hozzáad egy köbös Bézier-görbét az útvonal megadott helyéhez |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/hu/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Hozzáad egy kvadratikus Bézier-görbét az útvonal végéhez |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/hu/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Hozzáad egy kvadratikus Bézier-görbét az útvonal végéhez |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/hu/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Hozzáad egy kvadratikus Bézier-görbét az útvonal megadott helyéhez |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/hu/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Hozzáad egy kvadratikus Bézier-görbét az útvonal megadott helyéhez |
| [`move_to(self, point)`](/slides/python-net/hu/aspose.slides/geometrypath/move_to/#asposepydrawingpointf) | Beállítja a következő pont pozícióját. |
| [`move_to(self, x, y)`](/slides/python-net/hu/aspose.slides/geometrypath/move_to/#float-float) | Beállítja a következő pont pozícióját. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/geometrypath/remove_at/#int) | Eltávolítja a szegmenyt a geometriai útvonal megadott indexén. |
| [`close_figure(self)`](/slides/python-net/hu/aspose.slides/geometrypath/close_figure/#) | Lezárja az útvonal aktuális alakzatát |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/hu/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Hozzáfűzi a megadott ívet az útvonalhoz. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)