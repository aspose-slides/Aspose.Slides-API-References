---
title: IGeometryPath class
second_title: Aspose.Slides para Python via .NET - Referência da API
description: 
type: docs
url: /pt/aspose.slides/igeometrypath/
---
## IGeometryPath classe

Representa o caminho de geometria do GeometryShape

O tipo IGeometryPath expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`path_data`](/slides/python-net/pt/aspose.slides/igeometrypath/path_data/) | Retorna o caminho de geometria do GeometryShape como um array de segmentos de caminho. |
| [`fill_mode`](/slides/python-net/pt/aspose.slides/igeometrypath/fill_mode/) | Define o modo de preenchimento |
| [`stroke`](/slides/python-net/pt/aspose.slides/igeometrypath/stroke/) | Define a aparência do traço |

## Métodos

| Method | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/pt/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | Adiciona uma linha ao final do caminho |
| [`line_to(self, x, y)`](/slides/python-net/pt/aspose.slides/igeometrypath/line_to/#float-float) | Adiciona uma linha ao final do caminho |
| [`line_to(self, point, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | Adiciona uma linha ao local especificado do caminho |
| [`line_to(self, x, y, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/line_to/#float-float-int) | Adiciona uma linha ao local especificado do caminho |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/pt/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Adiciona uma curva Bezier cúbica ao final do caminho |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/pt/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Adiciona uma curva Bezier cúbica ao final do caminho |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Adiciona uma curva Bezier cúbica ao local especificado do caminho |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Adiciona uma curva Bezier cúbica ao local especificado do caminho |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/pt/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Adiciona uma curva Bezier quadrática ao final do caminho |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/pt/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Adiciona uma curva Bezier quadrática ao final do caminho |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Adiciona uma curva Bezier quadrática ao local especificado do caminho |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Adiciona uma curva Bezier quadrática ao local especificado do caminho |
| [`move_to(self, point)`](/slides/python-net/pt/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | Define a posição do próximo ponto. |
| [`move_to(self, x, y)`](/slides/python-net/pt/aspose.slides/igeometrypath/move_to/#float-float) | Define a posição do próximo ponto. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/remove_at/#int) | Remove o segmento no índice especificado do caminho de geometria. |
| [`close_figure(self)`](/slides/python-net/pt/aspose.slides/igeometrypath/close_figure/#) | Fecha a figura atual deste caminho |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/pt/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Anexa o arco especificado ao caminho. |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)