---
title: GeometryPath class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/geometrypath/
---
## GeometryPath Klasse

Stellt den Geometriepfad von GeometryShape dar.

Der Typ GeometryPath stellt die folgenden Member bereit:

## Konstruktoren

| Constructor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides/geometrypath/__init__/#) | Erstellt eine Instanz von GeometryPath |

## Eigenschaften

| Property | Beschreibung |
| :- | :- |
| [`path_data`](/slides/python-net/de/aspose.slides/geometrypath/path_data/) | Gibt den Geometriepfad von GeometryShape als Array von Pfadsegmenten zurück. |
| [`fill_mode`](/slides/python-net/de/aspose.slides/geometrypath/fill_mode/) | Setzt den Füllmodus |
| [`stroke`](/slides/python-net/de/aspose.slides/geometrypath/stroke/) | Setzt das Aussehen des Strichs |

## Methoden

| Method | Beschreibung |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/de/aspose.slides/geometrypath/line_to/#asposepydrawingpointf) | Fügt eine Linie am Ende des Pfads hinzu |
| [`line_to(self, x, y)`](/slides/python-net/de/aspose.slides/geometrypath/line_to/#float-float) | Fügt eine Linie am Ende des Pfads hinzu |
| [`line_to(self, point, index)`](/slides/python-net/de/aspose.slides/geometrypath/line_to/#asposepydrawingpointf-int) | Fügt eine Linie an der angegebenen Stelle des Pfads hinzu |
| [`line_to(self, x, y, index)`](/slides/python-net/de/aspose.slides/geometrypath/line_to/#float-float-int) | Fügt eine Linie an der angegebenen Stelle des Pfads hinzu |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/de/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Fügt eine kubische Bézierkurve am Ende des Pfads hinzu |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/de/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Fügt eine kubische Bézierkurve am Ende des Pfads hinzu |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/de/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Fügt eine kubische Bézierkurve an der angegebenen Stelle des Pfads hinzu |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/de/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Fügt eine kubische Bézierkurve an der angegebenen Stelle des Pfads hinzu |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/de/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Fügt eine quadratische Bézierkurve am Ende des Pfads hinzu |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/de/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Fügt eine quadratische Bézierkurve am Ende des Pfads hinzu |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/de/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Fügt eine quadratische Bézierkurve an der angegebenen Stelle des Pfads hinzu |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/de/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Fügt eine quadratische Bézierkurve an der angegebenen Stelle des Pfads hinzu |
| [`move_to(self, point)`](/slides/python-net/de/aspose.slides/geometrypath/move_to/#asposepydrawingpointf) | Setzt die Position des nächsten Punktes. |
| [`move_to(self, x, y)`](/slides/python-net/de/aspose.slides/geometrypath/move_to/#float-float) | Setzt die Position des nächsten Punktes. |
| [`remove_at(self, index)`](/slides/python-net/de/aspose.slides/geometrypath/remove_at/#int) | Entfernt das Segment am angegebenen Index des Geometriepfads. |
| [`close_figure(self)`](/slides/python-net/de/aspose.slides/geometrypath/close_figure/#) | Schließt die aktuelle Figur dieses Pfads |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/de/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Fügt den angegebenen Bogen zum Pfad hinzu. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)