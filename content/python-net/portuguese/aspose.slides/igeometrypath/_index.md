---
title: IGeometryPath class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/igeometrypath/
---
## IGeometryPath classe

Representa o caminho de geometria de GeometryShape

O tipo IGeometryPath expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`path_data`](/slides/python-net/pt/aspose.slides/igeometrypath/path_data/) | Retorna o caminho de geometria de GeometryShape como um array de segmentos de caminho. |
| [`fill_mode`](/slides/python-net/pt/aspose.slides/igeometrypath/fill_mode/) | Define o modo de preenchimento |
| [`stroke`](/slides/python-net/pt/aspose.slides/igeometrypath/stroke/) | Define a aparência do traço |

## Métodos

| Método | Descrição |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/pt/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | Adiciona linha ao final do caminho |
| [`line_to(self, x, y)`](/slides/python-net/pt/aspose.slides/igeometrypath/line_to/#float-float) | Adiciona linha ao final do caminho |
| [`line_to(self, point, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | Adiciona linha ao local especificado do caminho |
| [`line_to(self, x, y, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/line_to/#float-float-int) | Adiciona linha ao local especificado do caminho |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/pt/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Adiciona curva cúbica de Bezier ao final do caminho |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/pt/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Adiciona curva cúbica de Bezier ao final do caminho |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Adiciona curva cúbica de Bezier ao local especificado do caminho |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Adiciona curva cúbica de Bezier ao local especificado do caminho |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/pt/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Adiciona curva quadrática de Bezier ao final do caminho |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/pt/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Adiciona curva quadrática de Bezier ao final do caminho |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Adiciona curva quadrática de Bezier ao local especificado do caminho |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Adiciona curva quadrática de Bezier ao local especificado do caminho |
| [`move_to(self, point)`](/slides/python-net/pt/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | Define a posição do próximo ponto. |
| [`move_to(self, x, y)`](/slides/python-net/pt/aspose.slides/igeometrypath/move_to/#float-float) | Define a posição do próximo ponto. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides/igeometrypath/remove_at/#int) | Remove segmento no índice especificado do caminho de geometria. |
| [`close_figure(self)`](/slides/python-net/pt/aspose.slides/igeometrypath/close_figure/#) | Fecha a figura atual deste caminho |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/pt/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Anexa o arco especificado ao caminho. |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)