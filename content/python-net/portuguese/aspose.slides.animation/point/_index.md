---
title: Point class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.animation/point/
---
## Point classe

Representa um ponto de animação.

O tipo Point expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.animation/point/__init__/#) | Construtor padrão. |
| [`__init__(self, time, value, formula)`](/slides/python-net/pt/aspose.slides.animation/point/__init__/#float-any-str) | Cria ponto de animação com tempo, valor e fórmula. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`time`](/slides/python-net/pt/aspose.slides.animation/point/time/) | Representa o valor de tempo.<br/>            Leitura/gravação **float**. |
| [`value`](/slides/python-net/pt/aspose.slides.animation/point/value/) | Representa o valor do ponto.<br/>            Apenas: bool, ColorFormat, float, int, string.<br/>            Leitura/gravação **any**. |
| [`formula`](/slides/python-net/pt/aspose.slides.animation/point/formula/) | Fórmulas dentro de valores, dos atributos from, to, by podem ser compostas por:<br/>            Operadores aritméticos padrão: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Constantes: ‘pi’ ‘e’<br/>            Operadores condicionais: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Operadores de comparação: '==', '>=', '', '!=', '!'<br/>            Operadores trigonométricos: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Logaritmo natural ‘ln()’<br/>            Referências de propriedades (propriedades suportadas pelo host)<br/>            <br/>            por exemplo: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Leitura/gravação **str**. |

### Ver também
* módulo [`aspose.slides.animation`](/slides/python-net/pt/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)