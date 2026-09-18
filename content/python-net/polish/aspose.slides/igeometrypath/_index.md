---
title: IGeometryPath class
second_title: Aspose.Slides dla Pythona poprzez .NET Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/igeometrypath/
---
## IGeometryPath klasa

Reprezentuje ścieżkę geometryczną obiektu GeometryShape

Typ IGeometryPath udostępnia następujących członków:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`path_data`](/slides/python-net/pl/aspose.slides/igeometrypath/path_data/) | Zwraca ścieżkę geometryczną obiektu GeometryShape jako tablicę segmentów ścieżki. |
| [`fill_mode`](/slides/python-net/pl/aspose.slides/igeometrypath/fill_mode/) | Ustawia tryb wypełniania |
| [`stroke`](/slides/python-net/pl/aspose.slides/igeometrypath/stroke/) | Ustawia wygląd obrysu |

## Metody

| Metoda | Opis |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/pl/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | Dodaje linię na koniec ścieżki |
| [`line_to(self, x, y)`](/slides/python-net/pl/aspose.slides/igeometrypath/line_to/#float-float) | Dodaje linię na koniec ścieżki |
| [`line_to(self, point, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | Dodaje linię w określonym miejscu ścieżki |
| [`line_to(self, x, y, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/line_to/#float-float-int) | Dodaje linię w określonym miejscu ścieżki |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/pl/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Dodaje sześcienną krzywą Beziera na koniec ścieżki |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/pl/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Dodaje sześcienną krzywą Beziera na koniec ścieżki |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Dodaje sześcienną krzywą Beziera w określonym miejscu ścieżki |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Dodaje sześcienną krzywą Beziera w określonym miejscu ścieżki |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/pl/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Dodaje kwadratową krzywą Beziera na koniec ścieżki |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/pl/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Dodaje kwadratową krzywą Beziera na koniec ścieżki |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Dodaje kwadratową krzywą Beziera w określonym miejscu ścieżki |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Dodaje kwadratową krzywą Beziera w określonym miejscu ścieżki |
| [`move_to(self, point)`](/slides/python-net/pl/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | Ustawia pozycję następnego punktu. |
| [`move_to(self, x, y)`](/slides/python-net/pl/aspose.slides/igeometrypath/move_to/#float-float) | Ustawia pozycję następnego punktu. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/remove_at/#int) | Usuwa segment w określonym indeksie ścieżki geometrycznej. |
| [`close_figure(self)`](/slides/python-net/pl/aspose.slides/igeometrypath/close_figure/#) | Zamyka aktualną figurę tej ścieżki |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/pl/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Dodaje określony łuk do ścieżki. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)