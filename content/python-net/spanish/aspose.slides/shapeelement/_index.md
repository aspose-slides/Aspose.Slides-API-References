---
title: ShapeElement class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/shapeelement/
---
## ShapeElement class

Representa una parte de la forma con las mismas propiedades de contorno y relleno.

El tipo ShapeElement expone los siguientes miembros:

## Properties

| Propiedad | Descripción |
| :- | :- |
| [`parent_shape`](/slides/python-net/es/aspose.slides/shapeelement/parent_shape/) | Devuelve un Shape_PPT para el que se creó el elemento.<br/>            Solo lectura [`Shape`](/slides/python-net/es/aspose.slides/shape). |
| [`path_points`](/slides/python-net/es/aspose.slides/shapeelement/path_points/) | Obtiene una matriz de puntos que definen la geometría de la ruta del elemento. |
| [`path_types`](/slides/python-net/es/aspose.slides/shapeelement/path_types/) | Obtiene una matriz de valores byte que especifican el tipo de cada punto en la ruta del elemento. <br/>            <br/>**0**  Indica que el punto es el inicio de una figura.<br/><br/><br/>**1**  Indica que el punto es uno de los dos extremos de una línea.<br/><br/><br/>**3**  Indica que el punto es un extremo o punto de control de una spline Bézier cúbica.<br/><br/><br/>**7**  Enmascara todos los bits excepto los tres bits de menor orden, que indican el tipo de punto.<br/><br/><br/>**16**  Especifica que el segmento correspondiente es discontinuo.<br/><br/><br/>**32**  Especifica que el punto es un marcador.<br/><br/><br/>**128**  Especifica que el punto es el último punto en una subruta cerrada (figura).<br/><br/><br/>**129**  Indica un punto de datos que es tanto el extremo de un segmento de línea como el último punto de una subruta cerrada. |
| [`fill_source`](/slides/python-net/es/aspose.slides/shapeelement/fill_source/) | Devuelve información sobre cómo rellenar un elemento.<br/>            Solo lectura [`ShapeElementFillSource`](/slides/python-net/es/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/es/aspose.slides/shapeelement/stroke_source/) | Devuelve información sobre cómo trazar un elemento.<br/>            Solo lectura [`ShapeElementStrokeSource`](/slides/python-net/es/aspose.slides/shapeelementstrokesource). |

### See Also
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)