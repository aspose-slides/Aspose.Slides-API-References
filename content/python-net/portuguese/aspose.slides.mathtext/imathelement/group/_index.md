---
title: group method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.mathtext/imathelement/group/
weight: 70
---
## group(self) {#}
Coloca este elemento em um grupo usando uma chave curvada inferior

### Retorna

Nova instância do tipo [`IMathGroupingCharacter`](/slides/python-net/pt/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Coloca este elemento em um grupo usando um caractere de agrupamento, como chave curvada inferior ou outro

### Retorna

Nova instância do tipo [`IMathGroupingCharacter`](/slides/python-net/pt/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| character | **char** | Caractere de agrupamento, como CHAVE CURVADA INFERIOR (U+23DF) ou qualquer outro |
| position | [`MathTopBotPositions`](/slides/python-net/pt/aspose.slides.mathtext/mathtopbotpositions) | Posição do caractere de agrupamento |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/pt/aspose.slides.mathtext/mathtopbotpositions) | Justificação vertical do caractere de agrupamento.<br/><br/>            Especifica o alinhamento do objeto em relação à linha de base.<br/><br/>            Por exemplo, quando o caractere de agrupamento está acima do objeto, <br/><br/>            VerticalJustification de Top indica que o topo do objeto está na linha de base;<br/><br/>            quando VerticalJustification é definido como Bottom, a parte inferior do objeto está na linha de base |



### Veja Também
* classe [`IMathElement`](/slides/python-net/pt/aspose.slides.mathtext/imathelement)
* classe [`IMathGroupingCharacter`](/slides/python-net/pt/aspose.slides.mathtext/imathgroupingcharacter)
* enumeração [`MathTopBotPositions`](/slides/python-net/pt/aspose.slides.mathtext/mathtopbotpositions)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)