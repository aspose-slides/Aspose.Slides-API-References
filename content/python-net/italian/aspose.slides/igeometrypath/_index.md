---
title: IGeometryPath class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/igeometrypath/
---
## IGeometryPath classe

Rappresenta il percorso geometrico di GeometryShape

Il tipo IGeometryPath espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`path_data`](/slides/python-net/it/aspose.slides/igeometrypath/path_data/) | Restituisce il percorso geometrico di GeometryShape come un array di segmenti del percorso. |
| [`fill_mode`](/slides/python-net/it/aspose.slides/igeometrypath/fill_mode/) | Imposta la modalità di riempimento |
| [`stroke`](/slides/python-net/it/aspose.slides/igeometrypath/stroke/) | Imposta l'aspetto del tratto |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/it/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | Aggiunge una linea alla fine del percorso |
| [`line_to(self, x, y)`](/slides/python-net/it/aspose.slides/igeometrypath/line_to/#float-float) | Aggiunge una linea alla fine del percorso |
| [`line_to(self, point, index)`](/slides/python-net/it/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | Aggiunge una linea al punto specificato del percorso |
| [`line_to(self, x, y, index)`](/slides/python-net/it/aspose.slides/igeometrypath/line_to/#float-float-int) | Aggiunge una linea al punto specificato del percorso |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/it/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Aggiunge una curva cubica di Bezier alla fine del percorso |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/it/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Aggiunge una curva cubica di Bezier alla fine del percorso |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/it/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Aggiunge una curva cubica di Bezier al punto specificato del percorso |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/it/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Aggiunge una curva cubica di Bezier al punto specificato del percorso |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/it/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Aggiunge una curva quadratica di Bezier alla fine del percorso |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/it/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Aggiunge una curva quadratica di Bezier alla fine del percorso |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/it/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Aggiunge una curva quadratica di Bezier al punto specificato del percorso |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/it/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Aggiunge una curva quadratica di Bezier al punto specificato del percorso |
| [`move_to(self, point)`](/slides/python-net/it/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | Imposta la posizione del punto successivo. |
| [`move_to(self, x, y)`](/slides/python-net/it/aspose.slides/igeometrypath/move_to/#float-float) | Imposta la posizione del punto successivo. |
| [`remove_at(self, index)`](/slides/python-net/it/aspose.slides/igeometrypath/remove_at/#int) | Rimuove il segmento all'indice specificato del percorso geometrico. |
| [`close_figure(self)`](/slides/python-net/it/aspose.slides/igeometrypath/close_figure/#) | Chiude la figura corrente di questo percorso |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/it/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Aggiunge l'arco specificato al percorso. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)