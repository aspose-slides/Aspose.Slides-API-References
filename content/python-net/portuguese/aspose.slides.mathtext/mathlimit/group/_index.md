---
title: group method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathlimit/group/
weight: 80
---
## group(self) {#}
Coloca este elemento em um grupo usando uma chave curva inferior

### Retorna

Nova instância do tipo [`IMathGroupingCharacter`](/slides/python-net/pt/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Coloca este elemento em um grupo usando um caractere de agrupamento, como uma chave curva inferior ou outro

### Retorna

Nova instância do tipo [`IMathGroupingCharacter`](/slides/python-net/pt/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| character | **char** | Caractere de agrupamento como BOTTOM CURLY BRACKET (U+23DF) ou qualquer outro |
| position | [`MathTopBotPositions`](/slides/python-net/pt/aspose.slides.mathtext/mathtopbotpositions) | Posição do caractere de agrupamento |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/pt/aspose.slides.mathtext/mathtopbotpositions) | Justificação vertical do caractere de agrupamento.<br/><br/>            Especifica o alinhamento do objeto em relação à linha de base.<br/><br/>            Por exemplo, quando o caractere de grupo está acima do objeto, <br/><br/>            VerticalJustification of Top signifies that the top of the object falls on the baseline;<br/><br/>            when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |



### Veja também
* classe [`IMathGroupingCharacter`](/slides/python-net/pt/aspose.slides.mathtext/imathgroupingcharacter)
* classe [`MathLimit`](/slides/python-net/pt/aspose.slides.mathtext/mathlimit)
* enumeração [`MathTopBotPositions`](/slides/python-net/pt/aspose.slides.mathtext/mathtopbotpositions)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)