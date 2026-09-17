---
title: IGeometryPath class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/igeometrypath/
---
## IGeometryPath Klasse

Stellt den Geometriepfad von GeometryShape dar

Der Typ IGeometryPath stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`path_data`](/slides/python-net/de/aspose.slides/igeometrypath/path_data/) | Gibt den Geometriepfad von GeometryShape als ein Array von Pfadsegmenten zurück. |
| [`fill_mode`](/slides/python-net/de/aspose.slides/igeometrypath/fill_mode/) | Setzt den Füllmodus |
| [`stroke`](/slides/python-net/de/aspose.slides/igeometrypath/stroke/) | Setzt das Aussehen des Strichs |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/de/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | Fügt eine Linie am Ende des Pfads hinzu |
| [`line_to(self, x, y)`](/slides/python-net/de/aspose.slides/igeometrypath/line_to/#float-float) | Fügt eine Linie am Ende des Pfads hinzu |
| [`line_to(self, point, index)`](/slides/python-net/de/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | Fügt eine Linie an der angegebenen Stelle des Pfads hinzu |
| [`line_to(self, x, y, index)`](/slides/python-net/de/aspose.slides/igeometrypath/line_to/#float-float-int) | Fügt eine Linie an der angegebenen Stelle des Pfads hinzu |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/de/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Fügt eine kubische Bezier-Kurve am Ende des Pfads hinzu |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/de/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Fügt eine kubische Bezier-Kurve am Ende des Pfads hinzu |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/de/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Fügt eine kubische Bezier-Kurve an der angegebenen Stelle des Pfads hinzu |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/de/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Fügt eine kubische Bezier-Kurve an der angegebenen Stelle des Pfads hinzu |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/de/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Fügt eine quadratische Bezier-Kurve am Ende des Pfads hinzu |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/de/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Fügt eine quadratische Bezier-Kurve am Ende des Pfads hinzu |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/de/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Fügt eine quadratische Bezier-Kurve an der angegebenen Stelle des Pfads hinzu |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/de/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Fügt eine quadratische Bezier-Kurve an der angegebenen Stelle des Pfads hinzu |
| [`move_to(self, point)`](/slides/python-net/de/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | Setzt die Position des nächsten Punktes. |
| [`move_to(self, x, y)`](/slides/python-net/de/aspose.slides/igeometrypath/move_to/#float-float) | Setzt die Position des nächsten Punktes. |
| [`remove_at(self, index)`](/slides/python-net/de/aspose.slides/igeometrypath/remove_at/#int) | Entfernt das Segment am angegebenen Index des Geometriepfads. |
| [`close_figure(self)`](/slides/python-net/de/aspose.slides/igeometrypath/close_figure/#) | Schließt die aktuelle Figur dieses Pfads |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/de/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Fügt den angegebenen Bogen zum Pfad hinzu. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)