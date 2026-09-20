---
title: IGeometryPath class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/igeometrypath/
---
## IGeometryPath třída

Zastupuje geometrickou cestu objektu GeometryShape

Typ IGeometryPath obsahuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`path_data`](/slides/python-net/cs/aspose.slides/igeometrypath/path_data/) | Vrací geometrickou cestu objektu GeometryShape jako pole segmentů cesty. |
| [`fill_mode`](/slides/python-net/cs/aspose.slides/igeometrypath/fill_mode/) | Nastavuje režim výplně |
| [`stroke`](/slides/python-net/cs/aspose.slides/igeometrypath/stroke/) | Nastavuje vzhled tahu |

## Metody

| Metoda | Popis |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/cs/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | Přidá čáru na konec cesty |
| [`line_to(self, x, y)`](/slides/python-net/cs/aspose.slides/igeometrypath/line_to/#float-float) | Přidá čáru na konec cesty |
| [`line_to(self, point, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | Přidá čáru na určené místo cesty |
| [`line_to(self, x, y, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/line_to/#float-float-int) | Přidá čáru na určené místo cesty |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/cs/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Přidá kubickou Bézierovu křivku na konec cesty |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/cs/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Přidá kubickou Bézierovu křivku na konec cesty |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Přidá kubickou Bézierovu křivku na určené místo cesty |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Přidá kubickou Bézierovu křivku na určené místo cesty |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/cs/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Přidá kvadratickou Bézierovu křivku na konec cesty |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/cs/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Přidá kvadratickou Bézierovu křivku na konec cesty |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Přidá kvadratickou Bézierovu křivku na určené místo cesty |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Přidá kvadratickou Bézierovu křivku na určené místo cesty |
| [`move_to(self, point)`](/slides/python-net/cs/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | Nastavuje pozici dalšího bodu. |
| [`move_to(self, x, y)`](/slides/python-net/cs/aspose.slides/igeometrypath/move_to/#float-float) | Nastavuje pozici dalšího bodu. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides/igeometrypath/remove_at/#int) | Odstraní segment na určeném indexu geometrické cesty. |
| [`close_figure(self)`](/slides/python-net/cs/aspose.slides/igeometrypath/close_figure/#) | Uzavře aktuální tvar této cesty |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/cs/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Připojí určený oblouk k cestě. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)