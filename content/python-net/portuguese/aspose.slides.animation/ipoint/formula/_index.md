---
title: formula property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.animation/ipoint/formula/
weight: 10
---
## propriedade da fórmula
Fórmulas dentro de valores, nos atributos from, to, by podem ser compostas por:
            Operadores aritméticos padrão: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Constantes: ‘pi’ ‘e’
            Operadores condicionais: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
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

### Ver também
* classe [`IPoint`](/slides/python-net/pt/aspose.slides.animation/ipoint)
* módulo [`aspose.slides.animation`](/slides/python-net/pt/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)