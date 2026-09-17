---
title: GeometryPath class
second_title: Aspose.Slides para Python via .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/geometrypath/
---
## GeometryPath clase

Representa la ruta geométrica de GeometryShape

El tipo GeometryPath expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides/geometrypath/__init__/#) | Crea una instancia de GeometryPath |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`path_data`](/slides/python-net/es/aspose.slides/geometrypath/path_data/) | Devuelve la ruta geométrica de GeometryShape como una matriz de segmentos de ruta. |
| [`fill_mode`](/slides/python-net/es/aspose.slides/geometrypath/fill_mode/) | Establece el modo de relleno |
| [`stroke`](/slides/python-net/es/aspose.slides/geometrypath/stroke/) | Establece la apariencia del trazo |

## Métodos

| Método | Descripción |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/es/aspose.slides/geometrypath/line_to/#asposepydrawingpointf) | Agrega una línea al final de la ruta |
| [`line_to(self, x, y)`](/slides/python-net/es/aspose.slides/geometrypath/line_to/#float-float) | Agrega una línea al final de la ruta |
| [`line_to(self, point, index)`](/slides/python-net/es/aspose.slides/geometrypath/line_to/#asposepydrawingpointf-int) | Agrega una línea al lugar especificado de la ruta |
| [`line_to(self, x, y, index)`](/slides/python-net/es/aspose.slides/geometrypath/line_to/#float-float-int) | Agrega una línea al lugar especificado de la ruta |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/es/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Agrega una curva Bezier cúbica al final de la ruta |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/es/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Agrega una curva Bezier cúbica al final de la ruta |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/es/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Agrega una curva Bezier cúbica al lugar especificado de la ruta |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/es/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Agrega una curva Bezier cúbica al lugar especificado de la ruta |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/es/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Agrega una curva Bezier cuadrática al final de la ruta |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/es/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Agrega una curva Bezier cuadrática al final de la ruta |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/es/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Agrega una curva Bezier cuadrática al lugar especificado de la ruta |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/es/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Agrega una curva Bezier cuadrática al lugar especificado de la ruta |
| [`move_to(self, point)`](/slides/python-net/es/aspose.slides/geometrypath/move_to/#asposepydrawingpointf) | Establece la posición del siguiente punto. |
| [`move_to(self, x, y)`](/slides/python-net/es/aspose.slides/geometrypath/move_to/#float-float) | Establece la posición del siguiente punto. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides/geometrypath/remove_at/#int) | Elimina el segmento en el índice especificado de la ruta geométrica. |
| [`close_figure(self)`](/slides/python-net/es/aspose.slides/geometrypath/close_figure/#) | Cierra la figura actual de esta ruta |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/es/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Añade el arco especificado a la ruta. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)