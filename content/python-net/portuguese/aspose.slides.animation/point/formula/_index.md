---
title: formula property
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.animation/point/formula/
weight: 20
---
## propriedade de fórmula
Fórmulas dentro de valores, dos atributos from, to, by, podem ser compostas por:
            Operadores aritméticos padrão: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Constantes: ‘pi’ ‘e’
            Operadores condicionais: ‘abs’, ‘min’, ‘max’, ‘?’ (se)
            Operadores de comparação: '==', '>=', '', '!=', '!'
            Operadores trigonométricos: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Logaritmo natural ‘ln()’
            Referências de propriedade (propriedades suportadas pelo host)
            
            por exemplo: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Leitura/gravação **str**.

### Definição:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### Veja também
* classe [`Point`](/slides/python-net/pt/aspose.slides.animation/point)
* módulo [`aspose.slides.animation`](/slides/python-net/pt/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)