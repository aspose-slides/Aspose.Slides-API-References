---
title: IGeometryPath class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/igeometrypath/
---
## IGeometryPath clase

Representa la ruta geométrica de GeometryShape

El tipo IGeometryPath expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`path_data`](/slides/python-net/es/aspose.slides/igeometrypath/path_data/) | Devuelve la ruta geométrica de GeometryShape como una matriz de segmentos de ruta. |
| [`fill_mode`](/slides/python-net/es/aspose.slides/igeometrypath/fill_mode/) | Establece el modo de relleno |
| [`stroke`](/slides/python-net/es/aspose.slides/igeometrypath/stroke/) | Establece la apariencia del trazo |

## Métodos

| Método | Descripción |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/es/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | Añade una línea al final de la ruta |
| [`line_to(self, x, y)`](/slides/python-net/es/aspose.slides/igeometrypath/line_to/#float-float) | Añade una línea al final de la ruta |
| [`line_to(self, point, index)`](/slides/python-net/es/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | Añade una línea al lugar especificado de la ruta |
| [`line_to(self, x, y, index)`](/slides/python-net/es/aspose.slides/igeometrypath/line_to/#float-float-int) | Añade una línea al lugar especificado de la ruta |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/es/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Añade una curva cúbica de Bézier al final de la ruta |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/es/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Añade una curva cúbica de Bézier al final de la ruta |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/es/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Añade una curva cúbica de Bézier al lugar especificado de la ruta |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/es/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Añade una curva cúbica de Bézier al lugar especificado de la ruta |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/es/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Añade una curva cuadrática de Bézier al final de la ruta |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/es/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Añade una curva cuadrática de Bézier al final de la ruta |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/es/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Añade una curva cuadrática de Bézier al lugar especificado de la ruta |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/es/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Añade una curva cuadrática de Bézier al lugar especificado de la ruta |
| [`move_to(self, point)`](/slides/python-net/es/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | Establece la posición del siguiente punto. |
| [`move_to(self, x, y)`](/slides/python-net/es/aspose.slides/igeometrypath/move_to/#float-float) | Establece la posición del siguiente punto. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides/igeometrypath/remove_at/#int) | Elimina el segmento en el índice especificado de la ruta geométrica. |
| [`close_figure(self)`](/slides/python-net/es/aspose.slides/igeometrypath/close_figure/#) | Cierra la figura actual de esta ruta |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/es/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Añade el arco especificado a la ruta. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)