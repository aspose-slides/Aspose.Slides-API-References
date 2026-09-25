---
title: GeometryPath class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/geometrypath/
---
## GeometryPath classe

Rappresenta il percorso geometrico di GeometryShape

Il tipo GeometryPath espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides/geometrypath/__init__/#) | Crea un'istanza di GeometryPath |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`path_data`](/slides/python-net/it/aspose.slides/geometrypath/path_data/) | Restituisce il percorso geometrico di GeometryShape come un array di segmenti di percorso. |
| [`fill_mode`](/slides/python-net/it/aspose.slides/geometrypath/fill_mode/) | Imposta la modalità di riempimento |
| [`stroke`](/slides/python-net/it/aspose.slides/geometrypath/stroke/) | Imposta l'aspetto del tratto |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/it/aspose.slides/geometrypath/line_to/#asposeslidespointf) | Aggiunge una linea alla fine del percorso |
| [`line_to(self, x, y)`](/slides/python-net/it/aspose.slides/geometrypath/line_to/#float-float) | Aggiunge una linea alla fine del percorso |
| [`line_to(self, point, index)`](/slides/python-net/it/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | Aggiunge una linea nel punto specificato del percorso |
| [`line_to(self, x, y, index)`](/slides/python-net/it/aspose.slides/geometrypath/line_to/#float-float-int) | Aggiunge una linea nel punto specificato del percorso |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/it/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Aggiunge una curva cubica di Bezier alla fine del percorso |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/it/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Aggiunge una curva cubica di Bezier alla fine del percorso |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/it/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Aggiunge una curva cubica di Bezier al punto specificato del percorso |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/it/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Aggiunge una curva cubica di Bezier al punto specificato del percorso |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/it/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Aggiunge una curva quadratica di Bezier alla fine del percorso |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/it/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Aggiunge una curva quadratica di Bezier alla fine del percorso |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/it/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Aggiunge una curva quadratica di Bezier al punto specificato del percorso |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/it/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Aggiunge una curva quadratica di Bezier al punto specificato del percorso |
| [`move_to(self, point)`](/slides/python-net/it/aspose.slides/geometrypath/move_to/#asposeslidespointf) | Imposta la posizione del punto successivo. |
| [`move_to(self, x, y)`](/slides/python-net/it/aspose.slides/geometrypath/move_to/#float-float) | Imposta la posizione del punto successivo. |
| [`remove_at(self, index)`](/slides/python-net/it/aspose.slides/geometrypath/remove_at/#int) | Rimuove il segmento all'indice specificato del percorso geometrico. |
| [`close_figure(self)`](/slides/python-net/it/aspose.slides/geometrypath/close_figure/#) | Chiude la figura corrente di questo percorso |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/it/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Aggiunge l'arco specificato al percorso. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)