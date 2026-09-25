---
title: IGeometryPath class
second_title: Aspose.Slides dla Pythona – odniesienie do API .NET
description: 
type: docs
url: /pl/aspose.slides/igeometrypath/
---
## IGeometryPath klasa

Reprezentuje ścieżkę geometryczną GeometryShape

Typ IGeometryPath udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`path_data`](/slides/python-net/pl/aspose.slides/igeometrypath/path_data/) | Zwraca ścieżkę geometryczną GeometryShape jako tablicę segmentów ścieżki. |
| [`fill_mode`](/slides/python-net/pl/aspose.slides/igeometrypath/fill_mode/) | Ustawia tryb wypełniania |
| [`stroke`](/slides/python-net/pl/aspose.slides/igeometrypath/stroke/) | Ustawia wygląd kreski |

## Metody

| Metoda | Opis |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/pl/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | Dodaje linię na koniec ścieżki |
| [`line_to(self, x, y)`](/slides/python-net/pl/aspose.slides/igeometrypath/line_to/#float-float) | Dodaje linię na koniec ścieżki |
| [`line_to(self, point, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | Dodaje linię do określonego miejsca ścieżki |
| [`line_to(self, x, y, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/line_to/#float-float-int) | Dodaje linię do określonego miejsca ścieżki |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/pl/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Dodaje krzywą Beziera trzeciego stopnia na koniec ścieżki |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/pl/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Dodaje krzywą Beziera trzeciego stopnia na koniec ścieżki |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Dodaje krzywą Beziera trzeciego stopnia do określonego miejsca ścieżki |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Dodaje krzywą Beziera trzeciego stopnia do określonego miejsca ścieżki |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/pl/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Dodaje krzywą Beziera drugiego stopnia na koniec ścieżki |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/pl/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Dodaje krzywą Beziera drugiego stopnia na koniec ścieżki |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Dodaje krzywą Beziera drugiego stopnia do określonego miejsca ścieżki |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Dodaje krzywą Beziera drugiego stopnia do określonego miejsca ścieżki |
| [`move_to(self, point)`](/slides/python-net/pl/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | Ustawia pozycję kolejnego punktu. |
| [`move_to(self, x, y)`](/slides/python-net/pl/aspose.slides/igeometrypath/move_to/#float-float) | Ustawia pozycję kolejnego punktu. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides/igeometrypath/remove_at/#int) | Usuwa segment o podanym indeksie ścieżki geometrycznej. |
| [`close_figure(self)`](/slides/python-net/pl/aspose.slides/igeometrypath/close_figure/#) | Zamyka bieżącą figurę tej ścieżki |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/pl/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Dołącza określony łuk do ścieżki. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)