---
title: path_types property
second_title: Referencia de la API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/shapeelement/path_types/
weight: 40
---
## propiedad path_types
Obtiene una matriz de valores byte que especifican el tipo de cada punto en la ruta del elemento. 
            
**0**  Indica que el punto es el inicio de una figura.


**1**  Indica que el punto es uno de los dos extremos de una línea.


**3**  Indica que el punto es un extremo o un punto de control de una spline cúbica de Bézier.


**7**  Enmascara todos los bits excepto los tres bits de orden bajo, que indican el tipo de punto.


**16**  Especifica que el segmento correspondiente es discontinuo.


**32**  Especifica que el punto es un marcador.


**128**  Especifica que el punto es el último punto en una subruta cerrada (figura).


**129**  Indica un punto de datos que es tanto el extremo de un segmento de línea como el último punto de una subruta cerrada.

### Definición:
```python
@property
def path_types(self):
    ...
```


### Ver también
* clase [`ShapeElement`](/slides/python-net/es/aspose.slides/shapeelement)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)