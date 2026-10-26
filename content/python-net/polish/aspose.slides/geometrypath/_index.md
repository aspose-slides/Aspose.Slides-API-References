---
title: GeometryPath class
second_title: Aspose.Slides dla Pythona poprzez .NET referencję API
description: 
type: docs
url: /pl/aspose.slides/geometrypath/
---
## GeometryPath klasa

Reprezentuje ścieżkę geometryczną kształtu GeometryShape

Typ GeometryPath udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides/geometrypath/__init__/#) | Tworzy instancję GeometryPath |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`path_data`](/slides/python-net/pl/aspose.slides/geometrypath/path_data/) | Zwraca ścieżkę geometryczną kształtu GeometryShape jako tablicę segmentów ścieżki. |
| [`fill_mode`](/slides/python-net/pl/aspose.slides/geometrypath/fill_mode/) | Ustawia tryb wypełniania |
| [`stroke`](/slides/python-net/pl/aspose.slides/geometrypath/stroke/) | Ustawia wygląd obrysu |

## Metody

| Metoda | Opis |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/pl/aspose.slides/geometrypath/line_to/#asposeslidespointf) | Dodaje linię na koniec ścieżki |
| [`line_to(self, x, y)`](/slides/python-net/pl/aspose.slides/geometrypath/line_to/#float-float) | Dodaje linię na koniec ścieżki |
| [`line_to(self, point, index)`](/slides/python-net/pl/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | Dodaje linię w określonym miejscu ścieżki |
| [`line_to(self, x, y, index)`](/slides/python-net/pl/aspose.slides/geometrypath/line_to/#float-float-int) | Dodaje linię w określonym miejscu ścieżki |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/pl/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Dodaje sześcienną krzywą Béziera na koniec ścieżki |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/pl/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Dodaje sześcienną krzywą Béziera na koniec ścieżki |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/pl/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Dodaje sześcienną krzywą Béziera w określonym miejscu ścieżki |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/pl/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Dodaje sześcienną krzywą Béziera w określonym miejscu ścieżki |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/pl/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Dodaje kwadratową krzywą Béziera na koniec ścieżki |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/pl/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Dodaje kwadratową krzywą Béziera na koniec ścieżki |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/pl/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Dodaje kwadratową krzywą Béziera w określonym miejscu ścieżki |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/pl/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Dodaje kwadratową krzywą Béziera w określonym miejscu ścieżki |
| [`move_to(self, point)`](/slides/python-net/pl/aspose.slides/geometrypath/move_to/#asposeslidespointf) | Ustawia pozycję następnego punktu. |
| [`move_to(self, x, y)`](/slides/python-net/pl/aspose.slides/geometrypath/move_to/#float-float) | Ustawia pozycję następnego punktu. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides/geometrypath/remove_at/#int) | Usuwa segment o określonym indeksie ścieżki geometrycznej. |
| [`close_figure(self)`](/slides/python-net/pl/aspose.slides/geometrypath/close_figure/#) | Zamyka aktualną figurę tej ścieżki |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/pl/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Dołącza określony łuk do ścieżki. |


### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)