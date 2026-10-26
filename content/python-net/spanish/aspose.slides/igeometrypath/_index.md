---
title: IGeometryPath class
second_title: Referencia de la API de Aspose.Slides para Python mediante .NET
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
| [`line_to(self, point)`](/slides/python-net/es/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | Añade una línea al final de la ruta |
| [`line_to(self, x, y)`](/slides/python-net/es/aspose.slides/igeometrypath/line_to/#float-float) | Añade una línea al final de la ruta |
| [`line_to(self, point, index)`](/slides/python-net/es/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | Añade una línea al lugar especificado de la ruta |
| [`line_to(self, x, y, index)`](/slides/python-net/es/aspose.slides/igeometrypath/line_to/#float-float-int) | Añade una línea al lugar especificado de la ruta |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/es/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Añade una curva Bézier cúbica al final de la ruta |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/es/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Añade una curva Bézier cúbica al final de la ruta |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/es/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Añade una curva Bézier cúbica al lugar especificado de la ruta |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/es/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Añade una curva Bézier cúbica al lugar especificado de la ruta |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/es/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Añade una curva Bézier cuadrática al final de la ruta |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/es/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Añade una curva Bézier cuadrática al final de la ruta |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/es/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Añade una curva Bézier cuadrática al lugar especificado de la ruta |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/es/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Añade una curva Bézier cuadrática al lugar especificado de la ruta |
| [`move_to(self, point)`](/slides/python-net/es/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | Establece la posición del siguiente punto. |
| [`move_to(self, x, y)`](/slides/python-net/es/aspose.slides/igeometrypath/move_to/#float-float) | Establece la posición del siguiente punto. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides/igeometrypath/remove_at/#int) | Elimina el segmento en el índice especificado de la ruta geométrica. |
| [`close_figure(self)`](/slides/python-net/es/aspose.slides/igeometrypath/close_figure/#) | Cierra la figura actual de esta ruta |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/es/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Añade el arco especificado a la ruta. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)