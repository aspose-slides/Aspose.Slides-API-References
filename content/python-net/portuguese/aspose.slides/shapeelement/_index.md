---
title: ShapeElement class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/shapeelement/
---
## ShapeElement classe

Representa uma parte da forma com as mesmas propriedades de contorno e preenchimento.

O tipo ShapeElement expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`parent_shape`](/slides/python-net/pt/aspose.slides/shapeelement/parent_shape/) | Returns a Shape_PPT for which element was created.<br/>            Somente leitura [`Shape`](/slides/python-net/pt/aspose.slides/shape). |
| [`path_points`](/slides/python-net/pt/aspose.slides/shapeelement/path_points/) | Obtém um array de pontos que definem a geometria do caminho do elemento. |
| [`path_types`](/slides/python-net/pt/aspose.slides/shapeelement/path_types/) | Gets an array of byte values that specify the type of each point in the element's path. <br/>            <br/>**0**  Indica que o ponto é o início de uma figura.<br/><br/><br/>**1**  Indica que o ponto é um dos dois pontos finais de uma linha.<br/><br/><br/>**3**  Indica que o ponto é um ponto final ou ponto de controle de uma spline cúbica de Bézier.<br/><br/><br/>**7**  Maskara todos os bits, exceto os três bits de ordem inferior, que indicam o tipo do ponto.<br/><br/><br/>**16**  Especifica que o segmento correspondente é tracejado.<br/><br/><br/>**32**  Especifica que o ponto é um marcador.<br/><br/><br/>**128**  Especifica que o ponto é o último ponto em um subcaminho fechado (figura).<br/><br/><br/>**129**  Indica um ponto de dados que é ao mesmo tempo ponto final de um segmento de linha e o último ponto de um subcaminho fechado. |
| [`fill_source`](/slides/python-net/pt/aspose.slides/shapeelement/fill_source/) | Retorna informações sobre como preencher um elemento.<br/>            Somente leitura [`ShapeElementFillSource`](/slides/python-net/pt/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/pt/aspose.slides/shapeelement/stroke_source/) | Retorna informações sobre como contornar um elemento.<br/>            Somente leitura [`ShapeElementStrokeSource`](/slides/python-net/pt/aspose.slides/shapeelementstrokesource). |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)