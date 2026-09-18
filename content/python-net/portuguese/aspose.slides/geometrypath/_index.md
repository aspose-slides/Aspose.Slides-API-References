---
title: GeometryPath class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/geometrypath/
---
## GeometryPath classe

Representa o caminho geométrico de GeometryShape

O tipo GeometryPath expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides/geometrypath/__init__/#) | Cria uma instância de GeometryPath |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`path_data`](/slides/python-net/pt/aspose.slides/geometrypath/path_data/) | Retorna o caminho geométrico de GeometryShape como um array de segmentos de caminho. |
| [`fill_mode`](/slides/python-net/pt/aspose.slides/geometrypath/fill_mode/) | Define o modo de preenchimento |
| [`stroke`](/slides/python-net/pt/aspose.slides/geometrypath/stroke/) | Define a aparência do traço |

## Métodos

| Método | Descrição |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/pt/aspose.slides/geometrypath/line_to/#asposepydrawingpointf) | Adiciona linha ao final do caminho |
| [`line_to(self, x, y)`](/slides/python-net/pt/aspose.slides/geometrypath/line_to/#float-float) | Adiciona linha ao final do caminho |
| [`line_to(self, point, index)`](/slides/python-net/pt/aspose.slides/geometrypath/line_to/#asposepydrawingpointf-int) | Adiciona linha ao local especificado do caminho |
| [`line_to(self, x, y, index)`](/slides/python-net/pt/aspose.slides/geometrypath/line_to/#float-float-int) | Adiciona linha ao local especificado do caminho |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/pt/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Adiciona curva Bezier cúbica ao final do caminho |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/pt/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Adiciona curva Bezier cúbica ao final do caminho |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/pt/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Adiciona curva Bezier cúbica ao local especificado do caminho |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/pt/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Adiciona curva Bezier cúbica ao local especificado do caminho |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/pt/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Adiciona curva Bezier quadrática ao final do caminho |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/pt/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Adiciona curva Bezier quadrática ao final do caminho |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/pt/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Adiciona curva Bezier quadrática ao local especificado do caminho |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/pt/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Adiciona curva Bezier quadrática ao local especificado do caminho |
| [`move_to(self, point)`](/slides/python-net/pt/aspose.slides/geometrypath/move_to/#asposepydrawingpointf) | Define a posição do próximo ponto. |
| [`move_to(self, x, y)`](/slides/python-net/pt/aspose.slides/geometrypath/move_to/#float-float) | Define a posição do próximo ponto. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides/geometrypath/remove_at/#int) | Remove o segmento no índice especificado do caminho geométrico. |
| [`close_figure(self)`](/slides/python-net/pt/aspose.slides/geometrypath/close_figure/#) | Fecha a figura atual deste caminho |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/pt/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Anexa o arco especificado ao caminho. |


### Ver Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)