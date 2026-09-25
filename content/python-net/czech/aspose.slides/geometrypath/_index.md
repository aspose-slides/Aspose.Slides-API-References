---
title: GeometryPath class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/geometrypath/
---
## GeometryPath třída

Reprezentuje geometrickou cestu objektu GeometryShape

Typ GeometryPath poskytuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides/geometrypath/__init__/#) | Vytvoří instanci třídy GeometryPath |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`path_data`](/slides/python-net/cs/aspose.slides/geometrypath/path_data/) | Vrací geometrickou cestu objektu GeometryShape jako pole segmentů cesty. |
| [`fill_mode`](/slides/python-net/cs/aspose.slides/geometrypath/fill_mode/) | Nastavuje režim výplně |
| [`stroke`](/slides/python-net/cs/aspose.slides/geometrypath/stroke/) | Nastavuje vzhled obrysu |

## Metody

| Metoda | Popis |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/cs/aspose.slides/geometrypath/line_to/#asposeslidespointf) | Přidá čáru na konec cesty |
| [`line_to(self, x, y)`](/slides/python-net/cs/aspose.slides/geometrypath/line_to/#float-float) | Přidá čáru na konec cesty |
| [`line_to(self, point, index)`](/slides/python-net/cs/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | Přidá čáru na určené místo cesty |
| [`line_to(self, x, y, index)`](/slides/python-net/cs/aspose.slides/geometrypath/line_to/#float-float-int) | Přidá čáru na určené místo cesty |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/cs/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Přidá kubickou Bézierovu křivku na konec cesty |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/cs/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Přidá kubickou Bézierovu křivku na konec cesty |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/cs/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Přidá kubickou Bézierovu křivku na určené místo cesty |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/cs/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Přidá kubickou Bézierovu křivku na určené místo cesty |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/cs/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Přidá kvadratickou Bézierovu křivku na konec cesty |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/cs/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Přidá kvadratickou Bézierovu křivku na konec cesty |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/cs/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Přidá kvadratickou Bézierovu křivku na určené místo cesty |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/cs/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Přidá kvadratickou Bézierovu křivku na určené místo cesty |
| [`move_to(self, point)`](/slides/python-net/cs/aspose.slides/geometrypath/move_to/#asposeslidespointf) | Nastavuje pozici dalšího bodu. |
| [`move_to(self, x, y)`](/slides/python-net/cs/aspose.slides/geometrypath/move_to/#float-float) | Nastavuje pozici dalšího bodu. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides/geometrypath/remove_at/#int) | Odstraňuje segment na zadaném indexu geometrické cesty. |
| [`close_figure(self)`](/slides/python-net/cs/aspose.slides/geometrypath/close_figure/#) | Uzavře aktuální tvar této cesty |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/cs/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Připojí zadaný oblouk k cestě. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)