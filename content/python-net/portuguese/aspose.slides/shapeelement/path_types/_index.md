---
title: path_types property
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types propriedade
Obtém um array de valores byte que especificam o tipo de cada ponto no caminho do elemento. 
            
**0**  Indica que o ponto é o início de uma figura.


**1**  Indica que o ponto é um dos dois pontos finais de uma linha.


**3**  Indica que o ponto é um ponto final ou ponto de controle de uma spline cúbica de Bezier.


**7**  Mascarar todos os bits, exceto os três bits de ordem baixa, que indicam o tipo de ponto.


**16**  Especifica que o segmento correspondente é tracejado.


**32**  Especifica que o ponto é um marcador.


**128**  Especifica que o ponto é o último ponto em um subcaminho fechado (figura).


**129**  Indica um ponto de dados que é tanto o ponto final de um segmento de linha quanto o último ponto de um subcaminho fechado.

### Definição:
```python
@property
def path_types(self):
    ...
```


### Veja Também
* classe [`ShapeElement`](/slides/python-net/pt/aspose.slides/shapeelement)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)